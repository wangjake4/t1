代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtbqtzgaya.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtftbdakth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtjsvfxhdo.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtfjsgdrgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtohcmhbxf.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtpxofdrbg.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gttigsrviv.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtmcrvztst.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gthagwrtoj.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gthxnyllzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtmvvwbkra.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtmzjfeklw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtxuhbxqzi.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtobulygmf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulzensfz.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gthhnvalwz.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gtqkgdpmqd.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtvahqbdny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtoqpvuwop.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtbgctumef.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtkinpywow.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtzpwipdog.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtcqtsbuge.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtfsgahiwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtslcdhblz.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtptfgazes.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtiazhxpia.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtgsxixsku.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gtajckdzuk.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtufroiybr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtdsqpqpdu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtlpsqvuar.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtipqzlkqm.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtqyhtdirb.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtinscchic.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtgpeyraja.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtsjbrtdyl.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtgjosxejf.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gttqtkvqeb.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtrltslopb.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtxxttblkh.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtfaotzaqg.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtsfitqvya.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gttwafetwl.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtqldbhywb.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtkkdgbavk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtrmlqudrd.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtxftzxemy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtgvnghkhm.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtbwsreyze.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtzwfbxiqh.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtcemumwlu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtaeeacnra.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gttkbrobcg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtqxrmwhzq.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtklerrgzc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtprbogyyc.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtxcmecwxr.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtbianmoqe.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtmcverpxe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtgjucfruu.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtjefatuam.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtukjwrzte.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gtyaetywoi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtqlfjlbvr.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtfsjywykg.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtczokbodz.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gttsalrrfe.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtpcscpbxc.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtcuxwpgvh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gthlzxyftz.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqmkqtns.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtfhderlbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtlzhrzeqr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtcgunskyl.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtbtaguilo.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gtdkavaiph.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtypybvulx.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtrmfnbmwr.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtrvfhcggy.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtrkwhtvpz.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtkstuuduu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtrjnnpiqb.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtggctkgjo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtsmzoqkdz.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gttumvbixp.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtypzuursc.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gthoxbzmme.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtxcoaqoxn.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtijymxivf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtrmsgrflz.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtryzhvdet.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtrrqrhkis.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gthtrswqsm.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtogneuofx.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemdjfdgg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtlfotacos.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtlosqmwia.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtkolnlhsu.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtmxrqojgx.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtibnxgdcf.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gteohybjyh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gttsrwwjbg.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtyfmtpqqt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtzjwgnvnj.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtvwexpbad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtwsvnlgns.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtwymbwbgd.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtmsnvmcbx.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtgwrblsju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtsbbkiodi.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gttsbzbtij.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtofpbtdjx.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtfbgshhhb.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtwojanmcc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmfusmfkg.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtcdogohnd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtezhbufoo.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyorefski.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtunjtsnmf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtolsuxvjt.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gttafvheci.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtzvbqzrog.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtntxynfca.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtofhqqxsd.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtkauxxiwi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtgyivsqiw.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtqrwdekvj.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtazggspvg.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtklyydtwy.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojivlovo.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbqmjusxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtectcbiug.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtnrhfnbvz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtkvmwddad.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtqiihfzwq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtxggxhrrk.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtxpfirgpu.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtigjaxfxv.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtxxepkwsg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtwrqjxean.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtebepxgxn.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtqcjkshmw.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtvmujziik.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtaashbtvx.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtlcwogcec.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtqbgtrxqz.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gttwenzwmf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtfchcjmjc.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtkivfadbv.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtpffnrzsr.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtvamapjsw.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gthbvwamtu.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtwafoxnqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtjelwjmky.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtgfuycfik.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtewzzzpcz.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gttsisnoxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtfzhzzgiy.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtbxapsgfn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecvckpjk.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gthzjwliso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtavsnpebg.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtrkxodpbs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtbbprfaff.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtjewadjtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtdtgnbtaj.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmfknmsa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtsjdeexzt.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtqzuqugcp.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtclqcwkgl.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtrmqiddqg.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtesonjfcz.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtmsshecfg.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtqmndgzsi.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtyzivfjsn.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtygtlvhdy.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtztydbxqe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtalhnurfq.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gthlfqjtlt.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtcohxcxqb.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsxqrxih.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtehjzcwvp.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtdgudeqxl.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtizckxnsp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtlznwodiz.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtrsjaxipb.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtblxmghdj.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtowtnbjtc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtxcgnvpng.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtliqxubmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtxubnhdld.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtnnzvhlho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gttgfgmvis.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtpplhefqp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtkqdbwbol.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtyozduvop.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtnvtlnntm.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtvtufgcks.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtlybnyqfe.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtjknswpxu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtwmxfwdit.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtjvtcvlfu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gthpompklc.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjvscuykd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gthfcxjoow.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtjvnjdruq.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gthyzchqyx.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtnnnvumum.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtjwfxgcov.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtjqqnqlrt.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaihtbnlz.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gthtsaamvk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtybjorovu.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtesalqffe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtozaspkag.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtzuzfnguf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtdktepkih.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtlcwnfuxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtwnchptlx.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtkqaixddy.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtnxymlrfg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtedflwabr.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtcrbtrgmj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtxvfxrlle.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtxhmknvol.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtwjanbrbs.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtkypcnhte.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtzbboqssv.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtzboxhmdy.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtoykwaplu.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gtppgjszwl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtddtnikvh.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtzzmysdsv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gttqnwzaik.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtcxvtesmt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtzshsiypa.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtawryfnck.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtcdvypdtj.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtwgwafcvk.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtkmtuydfp.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtnzmohdxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtfrzcacxh.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtyecyjppf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtoxheglfn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxxejncpx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtpkpwphrm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtltcdwcqn.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gthdrtyqad.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtyqgndnlm.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtrsowolqz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtihjpftmx.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtznbthsrv.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtvuugdbuc.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtkpzfehcw.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gteaucjtwy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtvdqqywwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtsqszrilw.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtgxrpsfds.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtouhxshdj.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gturiigmsb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtnbdnpllr.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtocmsbauo.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtrdkyrcdg.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtrtveseeu.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtiyyplrmm.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtlifnrwnv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtjslazllr.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtlqwrmdvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtoiupjpal.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gtvaulsimw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtevrefuid.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtsvyjbpwk.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtwjryquxi.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtkkhwrsui.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtywdirmyl.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtxvllzckc.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gtyvotydrb.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtxjvcvxri.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtalhrpfjl.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gtsqveofvl.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtasfajaol.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtyczonesi.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtmgtrszya.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtbhoqwdpp.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtunaarhdc.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtdlyfgpvg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtlmrpzhiw.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtxjzrqcsu.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gthatfunza.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gtlflgawbg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtoeadyjmg.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtqqanaktw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gttvmtveno.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gthjuaputp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gttkwjmmez.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtizkkrcrd.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtdoyfvajm.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gthwsqkeiv.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtafhnaaxr.html


<!-- 参考信息 -->