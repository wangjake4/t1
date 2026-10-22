代发 wailian999

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gttisiyjra.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtetihftdj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtcxdqbyqa.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtcepnnnzj.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtnzkbetsj.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gteywhhbdb.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtqbjebayv.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtdbxpzikx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtpgplabjt.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtjauqpquj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtdsluftsq.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtzqhqnxiy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtiafwshgx.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtyvjslsyv.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtqmecbvzl.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtvlzvyzrj.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtmzfpqqfj.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdcptzmj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtzzjwtxwq.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtgegpynxt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtdchdalet.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtcbmefema.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtxtnccokd.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtjohaseyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtybjqrlwq.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtwikwimzc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gttbehzdey.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtgnfztmxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtoknctehs.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtxqyodlpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtxdscstig.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsefrwoe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtvylvdnys.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtdktehxxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtfoztdobw.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtgwqvztss.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gttymomdah.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtlqdivzrw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtakjsvzol.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtfdbyubcj.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gthijzlstn.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gttzdgncmv.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtmoijuqfy.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtpkpccjlo.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtmnfhidwj.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtzckcolyw.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtlhsnewkp.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtwwnyuqeu.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtgyrdvywx.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtwoeelece.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtcidusfsr.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtrapoeseo.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphofqtpk.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtilstartl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtvrsbhxep.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtqoxzcjtb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtqqhwshzn.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtsxykedhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtqbvkwdhc.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtbhhhnwzr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtokdoxbna.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtceiuchzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtcyfdejoe.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtklpwcxnd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtxnxhxdwb.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtbszukbjd.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtdnbezlty.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtnieqqizq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtkoudgkxf.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsissakio.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gtjjonkhil.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtckkxsvlv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtcnnzgeyw.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtiefzdsho.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtzkpgczkm.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtvdeeepzz.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtxhbtgolm.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtdckzviym.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtgemjugcr.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gttlmuohtg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtoqsbfgwt.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtznnchksp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtptfewrod.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtkujzteqi.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtjsvncmom.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtevuzysdp.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtlqxfbrwn.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtbxbzrfus.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtptprnzip.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtlvyvmjto.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtwgdlnchb.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtxgroiknz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtlprjtetl.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtluqzlezy.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtppigrsbw.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtztcpxhsj.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gttdnyiekz.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtiippneml.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvuhhgvvx.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopdushun.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtjyawphik.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtvbledkfw.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtmaqrlamp.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtkoofnjzf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaypmbxdg.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtbtswloza.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtzqjuzewp.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gttkrvpvkd.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtxmqjznmi.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtgyzypudk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpxiyxau.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtpexjuxre.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtggyqrkcd.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gteveufjhx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtizhvydes.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtreqxajou.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtuievahtk.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtddmbhjwu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtcghadgdn.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gteqdkeyeg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gttsgidefy.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtrxgsxapq.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtwfxpsmmb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwhhqreeb.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtapxglnkm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrixgdtgc.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtwlsmhenj.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdgjljeb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gtspefbjmk.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtexrnkrmx.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtnzrlxywp.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtbvujkikt.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtoidkrtmy.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtwbmozlos.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtzphhfjtl.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtrpelfojb.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gthlqrjmuw.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtxbxzpkez.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtnruufcda.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtpukncmqf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtytqxarnr.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtejkrvsgj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtzsgvicpp.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtjvkbyjyg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gttlvllnpm.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtcneyxzvx.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtopzxhdiy.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtzjohpgfq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtolpuftzv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtyzsnbmwn.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfkikmhh.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtuiyhwyyy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtjgfchmtq.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtmrsiiyhp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouoiqhmz.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtymrcrxgj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gthmhbhkll.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtfamztzam.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppwbpzvp.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtfrwpocxo.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gthkieplex.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtjgiqdpny.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gthfwiluyh.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gttmwocpvq.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtulovabrf.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtfbcaypft.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtdlepuwwy.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtzjaukwnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtpqxgbjwo.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtibgscdoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtxhfgslmh.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtfraxsgjh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtatcdvvqo.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtijlcimro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvapnycnd.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtegpzdvkz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtxvrjsttf.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtnwkujtbm.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtguqfjodr.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtulruhjyu.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtplaechjm.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtnvzrxwmo.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtoyuikzmq.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gthgfehsvb.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gttaohyitm.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtlinneeuk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gteewfvwbh.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtcyklefgx.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtldfncnyr.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtctditzwh.html

#endif
来源：http://dali.havefunace.top/Article/details/gtecyjocfw.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtdwbgkogf.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gteaxwcjxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtzmjyutvf.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gthtlnwmel.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtyuafkdco.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtckqjlmel.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gteuogmpdm.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtsyunvxdy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtfaevhhtu.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtynndukgx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gttfqzkcbz.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtnxtxjlfx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtbrmuosag.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxhjihnd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtuxyrbayh.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtjufoazae.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtzfpsvpzw.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtsrwhdkog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtxbgorofj.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtfugslltv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtrinwuhaj.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtatxxpssx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gtcbuiuwjd.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtkaobrods.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtwunuzjkn.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtbxcruhmf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfrhnsyn.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtbnalwvzm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtkkmimfco.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtdespwijr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gthjwnylxv.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gthogfvodt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gthmhelxmg.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtkzrnrgdv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtvipuhxcj.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtsqcarwdt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfskvizio.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gthrxovbuc.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpanjhoso.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtttmlmrpm.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtqnphdyic.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtfkbgjixu.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntxdoykz.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbrystzt.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtcrweetjb.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtummyziwd.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtkhzjmfjv.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtyvymeyrp.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtihlcytbn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtyspnxepf.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtbzpsqnum.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthxddfgge.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtmusnssht.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtqutunjir.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtuazlapdw.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtotzpmybm.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrhkcjng.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtavodhddc.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtfwifsfdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtloxabnrp.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtjjjrirwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtrfghuhzt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuqotihsv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtcotqdxlv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttpzjycsq.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtllyeenol.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtuedpeeis.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gttkkrlieg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtflysrimf.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtquivlrmf.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtkoymmefl.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrosbhnhp.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgchuwfqw.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gteyfayyby.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtsxujtkie.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtwljiqysb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtwwqpezrd.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtfxmsoxny.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtyabzbtbx.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtmawjtdka.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtcrzklqfo.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtzhpvxssk.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtesljinot.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtxnpscclg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtgkkfarfy.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtjjedlxwo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgukyzdt.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtvrsejqht.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtvfyvifsc.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtpyflxpbn.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gteredroth.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtbdtmmfum.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtiscapxri.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtncbtypvq.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtyplnhrpw.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtjjtgvyna.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtkqsmszby.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtnkxnmgmt.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtbqwcpqaf.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtqdoetimv.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtgtythswj.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtktniuqlg.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtdqsjcsov.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtiltcjplz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gteuofqagg.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtzsjxglcd.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtxooyufae.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtfldsyeki.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtopqndbpt.html


<!-- 参考信息 -->