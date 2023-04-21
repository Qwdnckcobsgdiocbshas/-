# -#include<stdio.h>
#include<string.h>
main()
{
	int a,b,c,d,e,i,j,z;
	
	
	
	printf("1 登录\n");
	printf("2 注册\n");
	scanf("%d",&a);
	switch(a)
	{
		case 1:goto one;break;
		case 2:z=0;break;
	}
	if(z==0)printf("暂未设计注册界面\n");
	one:printf("账号：");
	for(i=0;i<1;i++)
	scanf("%d",&b);
	printf("密码：");
	for(j=0;j<1;j++)
	scanf("%d",&c);
	two:printf("请按6确定登录\n");
	scanf("%d",&e);
	if(e==6)goto zero;
	else goto two;
	
	zero:printf("1 聊天助手\n");
	printf("2 视频广场\n");
	printf("3 出发游玩\n");
	printf("4 积分盒子\n");
	scanf("%d",&d);
	switch(d)
	{
		case 1:goto twoone;break;
		case 2:goto twotwo;break;
		case 3:goto twothree;break;
		case 4:goto twofour;break;
	}
	twoone:printf("主要陪伴老人聊天，分享趣闻轶事，根据聊天记录分析出用户的偏好"); 
	twotwo:printf("根据聊天智能分析用户偏好，推荐其他人发布的游玩视频，增强用户的信用度");
	twothree:printf("根据偏好重点推荐相关地点的旅游团或个性化定制导游，旅游地的商家可以进行入驻，并不时发布优惠券");
	twofour:printf("在平台下单旅游 ~ ~ ~查看老人的定位及旅游动态"); 
}
