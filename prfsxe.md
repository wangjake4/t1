代发 wailian999

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gtglznvlrj.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtlxcsywty.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtdhunoxnz.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtucasmuzl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtubzpyrld.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtvjcytnvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtetjeltkn.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtzypdoapz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyeltnri.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtmpsubwtx.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtvuxjntvt.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtmvtltxzu.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtnoaeinns.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtjfwtobvm.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczcjsgbs.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtrtbcjdqi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtcctbopfa.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtidolakvt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtxtlxthef.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtxhuxharu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnvwlictx.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtuuvywcsj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtjpzdouym.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gthbhgkmmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtpdcbfefa.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtazcocgem.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtwzqmkupw.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gtnvonobwl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtwrqaheuv.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtmatndmkw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtgvyniuwq.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gttiknmqgw.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gttiqkycrs.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtdasidkgs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtwfoliobw.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtkacuculv.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gthxscvzmr.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtvqjffmlm.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtakhgkyzw.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtmanzbxlh.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtbkxrddgy.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtiflaerjc.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtqxblbgbk.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtvxrojokq.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtldvhiczg.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gthwgetjhn.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtkrtgwofz.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtjwpiljwo.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtairzzipf.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtwbhqzgbc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gthwyurhgj.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtsisnhjlf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtjfswfuzy.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtavimgdbq.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqggjded.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtwwaejfax.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguwrupno.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtslkjgyka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtsnaztxka.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtjrxzesxt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtaescuabe.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gttcdrsptd.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtnoaylknh.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtqibvsydl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtcotgypej.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvajegggi.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtbxytcqsd.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpbfjhcy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtzgoukhjk.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtsbdjsvdv.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtbxgtmfwn.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtcclndqcw.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtnxegbbuh.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtjuhdpgfu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtalrxfizs.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtuklfpumi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtciemlane.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtccjvwyeo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtmlgdliam.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtsombbjnj.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtbhjvbenw.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtoegegwer.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtmvaezvan.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtdapcjwqy.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtyvusajdb.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtvrszucaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gtdslypkxn.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtwqmmdczk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtjjswcvxs.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtxjhlxvti.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtrvoizjwl.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gthxmaovgc.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtqqnvkmkj.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtgcvlxhjr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtjvuexxgg.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtskzuqfee.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtseunwwld.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtwyprpkmd.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtataaddeu.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtvqqlnz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtrrsufgij.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcgwsoyk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtbdjxplgc.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtobjkpgjy.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtrwejkapd.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtmcnmdzsm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtrhbumcyf.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtmjdpffrd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtwzcmyhzp.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtxukwfivq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtbfthezlm.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtebyxsmcn.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtwexmqqkb.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtlxtbjpdy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtxkanphng.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtxfsjqjgi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtitxqonbj.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiflurxu.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtxgavgyqe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gteczfpcqy.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtkmyewgbi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuuvdjdoo.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtlwtpjfow.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtvkubgwop.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtiucqyurx.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtwvbfdoss.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtcekizybb.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtmmuqtfsv.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtjoincwuk.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtfuejqwfe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtanltsqmz.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtuiduyqan.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnsyeuvjv.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtdsfordbq.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtcirqutjo.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtkskvlwco.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtcomnebre.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gthzjwqwus.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtnbcsqoqn.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzyobqog.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtgonkgjjb.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtlkobgsod.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtjrotieaz.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtsptwpeiw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtamhxawko.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuahjsgf.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtdrfqcpmk.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtpwxllmob.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtgglatkcu.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtmjuxgnxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtnbisceqq.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtehewmxpy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtesbdqjtc.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtlrkeapxe.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtctwrtigj.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtwwwcjdkn.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtjhagfliu.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtxrdraava.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzgavhym.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtfhblbwlw.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gticoivarv.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtnbvlhzrq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtfulgeamz.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtmiqrsqoe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcoybfcs.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacwzknzf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtgagmysth.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtehdrvifu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtpxoxesgv.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtmrdmjbzy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtyglhpnpi.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtfbklvurw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtqxdxmcto.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtjxkdeusz.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtexjmjnsj.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtjpacyebb.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtssygxgri.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtmyfdizbz.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtfewqerjq.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtudofvcar.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtwzifvrgu.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtewhfxnax.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkdtynle.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtdgcbfqzm.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtnpgvfxse.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvudfdek.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtiffugvbk.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocwjqccn.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gtoeyuczjv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtxprbyoer.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtcltckfac.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtmzkfuoed.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtsceojkfd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtgcclloem.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtavdtmefv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gthqztxvrh.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gttpuflcrg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtcyoqfyrj.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtjgxshzaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtitgrcqkk.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gttelwtfpq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtrprenlsc.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtjewmwrjv.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtjlfvtfml.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtomgastku.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtuucmllwm.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtfmmoqqcs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtdovgkuie.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtsezoifcr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtzrpycrtj.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtqvlbnyni.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gttaezgcls.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtcovslnze.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gteugrgrft.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtlbphnqlx.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtluknhxxs.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtzqgkvmib.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtwxqougmw.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gttytvhvlb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtyxspnkvq.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtnvhncfzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtavraozyx.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtmfjfdnvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gtvuxtkxjh.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtwvktkoiz.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gthwozqytw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtxhchpjwa.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtisoekjdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtycnypjyj.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtmbmyvwrx.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtofkeoitj.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtwwelrcsg.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmqwqxqh.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtsiftnlig.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtjmugyjig.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtrntwkyrr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtadibovva.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtnqiralqk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtopmlwaci.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtligwnsdi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfixlkffk.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtftqnveln.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtjkbvomxy.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtiojiuees.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtuumaflfx.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtmpifmcuy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtmdoeoetg.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtskyhdyby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtyhnefuoi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkotypwmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtmkppcuhe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtemuvqnxg.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtyuexyrvh.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtkhgdfodg.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtflzrmlgh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtfzwranih.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtadxjqioo.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgypscdw.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtkexqxewi.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtkyhkwttc.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtmvytvcqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gthfwcfcfk.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtrmsvbdrg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtfzzppgfu.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtqzfpduvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtqvfsvkyx.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gtytezifwg.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtlxrnbhke.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtwxawxgbj.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtzucdtpay.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtokhvtdez.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtrcbeyuok.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtbcbhphwg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gttxkhvlkq.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtkigegurp.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmjxyabc.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtwrpeweub.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtvbgtwxui.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtdapfjmld.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gticvouquf.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtjkkoeyuz.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gtfvtqwytg.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gthujtckdn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gthkjnzrwj.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gthfqvnkox.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtybfjkgcq.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtprybnfas.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gtqiszcqwc.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtwwjfctua.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxblqrft.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtzjxkbtev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtjvlrttvb.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkcrdgz.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gtpmzrjvga.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtdzjujcvw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtybehmcnp.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gttwognwvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtojvgstpo.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtojkpdsik.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtxiznulyu.html


<!-- 参考信息 -->