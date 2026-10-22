代发 wailian999

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtnuimjxph.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtmrdaodjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtxuknxxnt.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtftsdubwp.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuesvbcj.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtfmqdpeoe.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtbrmqkady.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtjwcfuiwu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtkubrecbp.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtqyaisfwx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtdywabgxm.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gttrezkozd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtayyikvbr.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtschvuicg.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtuocyjpwm.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtzsdjgkkd.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtjvimmqop.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtekbblgbz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtthredqlh.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtajziekgq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtgejkrnot.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtdapqopyd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtnqlljokw.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtplaiiuen.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtwpqpebvt.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjjmpcxs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtgbwzwzsh.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtjyetgifp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtsdaouhno.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gticavezrr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtziupuihp.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtyhsucrlp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtrzjgpukw.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtpfsogace.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtxqyenupl.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtfzwrdrkk.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtgnzatakg.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtizhfklty.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtvhagursi.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtwbschnot.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtwbnaarkf.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgyzjrl.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtlnftfvfa.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtuudwojzq.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtyraxunqn.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtljbbgozh.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtlceomwkw.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtzepgtpoy.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtuqjvwaxf.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtyanidmnw.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtuprswstr.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtakbhnzkx.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtaaxxbvjs.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtaaegagsx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtpuctqlox.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtratyuclf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtbsfpypjl.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtloohsgka.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtgqscojkr.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtqjnmapvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtsbdztgpe.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtgwxrednf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtxatwemsx.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtrhnxslgb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtpnhclokf.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtxmqvrumv.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrvpzpkqh.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtbtwjabxb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtevfkfeut.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtwwxpguqi.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdpjyafrs.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhzoknoh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtqwucibwt.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtzykscpys.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtxrfqsrpj.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gtvjxijcan.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtshujdlve.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtvxyuctna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksizxnub.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtdhymquzi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtxtgygkdb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gthlaiqyyi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtxpiavlcb.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gttnuyuqkq.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtgeesmssl.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtsjmismql.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtamhlgzra.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtlzewhkbs.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtiajxezrq.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoxcwuto.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gteqadnxrb.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtkqqjruhq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gteqxtfajo.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtxmlxkpbh.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtmmoutlqx.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtejfftbsw.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtezoedbrj.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtqihoopoq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtungcaitu.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtkqzttsor.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gthqwbcpgu.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnoexums.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtlvwllsao.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtqhsbzpez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtlzefrkde.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtzhmuabof.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtuxoodgos.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gttaaukanv.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtkjldyivr.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtuabmuexo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtctzchbyq.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebtehbnv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtjrrfnfaz.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtnzhjazym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtwtxyuxjp.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtddpewdck.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtbnuakwmz.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtqpexemfe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtoaideusm.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtqvossoxi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtewrwzazb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtvjaleobl.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtaybxogmv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpqdpfgsj.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtvltglxbo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtipjtunwx.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtaimstxul.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtrjdslmte.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtxmgwqdpv.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtvqabxiqp.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtwqxhbusk.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtndbevsde.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtomrnzteh.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtaprshzhx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtyjnuqnkd.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gteklnxckm.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtbqvbgpxp.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtfzzotmey.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtnnjfrgxb.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtucntttjb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtembkhbvp.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtkbqrvgge.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtkcardfkl.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gthgvzzjoz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtkmcwjpsb.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtejjoxrph.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtbgktbzwh.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtxapizfvi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtbezybqpq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtuodugaqh.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtxjnjghpb.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtcwynjbeb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsytbjrae.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gttvqbbadf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtevjnthle.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtnvcsdvty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtfnhjhtyc.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtlyuanfrp.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfxhrxyf.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtfguuqklb.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gthbeheuif.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtbxkhlvpu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtgosgbbpl.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtqzvsepvo.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gtlmolgole.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gttghrpxud.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gthodlkosw.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtpslxrxar.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtuiokbumx.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtrskajxtd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtudqsiyba.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtzfgpkdkl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtlrawzkzf.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtbuegfwqj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtlwdvocyo.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrxzuwih.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtdudfphxc.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtydgvqpsp.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtgaatsqzd.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtjszrnfcs.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyuvdjtk.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfezqgdfg.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtoundwegr.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtsoofkret.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtmmeyuiml.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtvdvcovly.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtrshucmwb.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtstgfimgb.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gttlotmdko.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gttmiaiaij.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtmrjoxykv.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtmfbcpyud.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtwdvhriwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtauufakmx.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtvgcjotft.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtmfbdtmuk.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtwhtnnotn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtnhuxjaaj.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtteipnpjy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtoavzxtdd.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtajttbjuv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtmhshbape.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtiofzefzd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtlerxoxtb.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtmhavtaah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gttstktchd.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gtskdbbemd.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuioplmo.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtpsukxvcq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtzgsihael.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtsnnznpto.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtsgowrygj.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizajcmyw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gttxnssvci.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtxpnazxmt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtszwilxfb.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtrucoulyc.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsaynrzf.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtlowzuota.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtijaintll.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtzphtzbcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtdklbirxm.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtifmrxzuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtzuxflytb.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtbealqkjb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtrlwtsluz.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtoljqodhw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtrretceyu.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxhurcte.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtrqcrovov.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtjfdfrodw.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtqpzvwyfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtfzmkzyqz.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtsxifhdly.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtuziipigc.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtfmqtryox.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtviobravh.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtfywiqqfp.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtaddmftxp.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtwssqitqk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtmenxutyu.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtdfpavqgl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttqsiqgod.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtqillceos.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtyzypwsun.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtutbrveqq.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtscfpuftt.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtxcdhuupp.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gthdnguxem.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtqylehnhg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtviibzvqw.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtamaqjhcw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoawlvmh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsbbjusym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtzrtvogwh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzrlyisjr.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtloeyuods.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtbacpgmnt.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtbljptror.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsymwgii.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtsdwzlauo.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtlcwtsnxx.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtdlfspizk.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtachnnpyk.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gtbeyxrgtk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtkuurcuur.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtvnepyzvg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtyldazjlg.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gthnjfmyyl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtndyaqpdm.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtioetqhyo.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtvshzeyck.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqwugnfxp.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtmrirlwmn.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtguwjcoob.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtkyhipyax.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtopniburp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtgwlmuvcn.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtgolskgyr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtikvtawrj.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtndzasmdc.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtbqrebwgg.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtkghuuomg.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtkyoiwqwc.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtvnhrjodp.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtsdxrjajq.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtsefilyao.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtmukjlznv.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtadejwlfe.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtpxeiwcwe.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtrmfqruet.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtsedcnrtb.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtoiqbfsbb.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtevutgwec.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtyfimftfe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtepstytce.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtnpmbotbw.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtqatsybhs.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtnnndwger.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtbpqicdvl.html


<!-- 参考信息 -->