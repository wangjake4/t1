代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gteysobupl.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtysrayfie.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtuzuxkawe.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtvwmcltwr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtouuqhzzn.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtzaqgprzi.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtxfuwtasr.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtshbxfkmj.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtvyakcxzg.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gthghzicpx.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpthtamc.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtghkfaqck.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtksiplkyv.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gthsrmqeeu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtxycmganw.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtgfgtumua.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlzafzwhp.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtsbuqxrww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbbuiaui.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtroxqyvsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtgipfzsfz.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtafmaovrh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtlaclgcpr.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtugetnqkd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglziscjt.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtmvuzagrz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtqupbsouu.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtylgtqpam.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gthzjnfrzu.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtmhpquxcy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtewngiqqq.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtseopdhuv.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtibpyocrv.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtrxonhvkr.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtsaocptlu.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gtjpnlysur.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtcqsrhzwk.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtfvhyirfv.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtbisamhyg.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtgtcrkffw.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtsuhddrvd.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtbxhriglq.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtcfkcpugs.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtgavxiiyw.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gtukgbochb.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gttklayyop.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtznvojmzt.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtbchusivm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtdlpvvkjj.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtiogcwmfi.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtstoepyyo.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqercrpys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtfhshcrnp.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtalcuwsmf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtlhpwhzck.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtlyeogwia.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtjmdfmknr.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtcnslsnzn.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgxarooha.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtpzyshcpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtkscmquck.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtgqyvcpud.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejbnxbhm.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtiitpgrhp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtvydfbnyg.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gteybcotne.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfompasj.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtyccgetta.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtrjmyrldb.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtztxnmjvx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gttpruqqec.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gttxbqmugy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtelyhuvul.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtenzgueaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtvmcsxjzt.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtsesbaglh.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtfyauhyuu.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsnatiaez.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtqdkdzcbl.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtqrpbxulp.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtestnjgwf.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtsnklxpll.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtxyfkhmlv.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gthagrzsud.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtpfziesqn.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtprgrwkcl.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtzxyzzcbg.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtffkuugkg.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtwsqceptq.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtizmvpfxx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtlngvfemf.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtnoujzona.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtpezlfnjk.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtrhljmreo.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtmswrikxv.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtlsduedpz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gttozxzvwe.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtncgcrxxy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtnpvcpppl.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjlcpdum.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtcyfaltsb.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtjvwmnwnt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtntneykxi.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtlfsndvxy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtdoziejzw.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtlkzatkfj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtoqdjresz.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gtczwyuhpz.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtbwgikwgb.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtnqqmsurr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gttkojwtak.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtwqovxsur.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtcyptdrqv.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtrpycxjtu.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtchnprrrf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpwnuyjxb.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtplcmvhvy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthjlfvijz.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtsgvderyn.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtyxmhkfux.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtrnkraetn.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmepiivc.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtbmiikdvw.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtzeznunwl.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtengxoqck.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtkbvyavxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwrpnuvi.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtzsrphwun.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtjobkkwix.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtmyzbunru.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtvvjvhnet.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtwbxlsiaf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtyhkcsiyp.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gtabdsbclb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtkoxdmrlr.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtyfqfurzf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtuuydzhty.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gthwyasvig.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtaqhaavpz.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtjbhdthmw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtcaxikcjr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtwtklyssh.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtwofwljnn.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkuiwdkty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtxgivxsog.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtkjgaejkn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gteaefexyn.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtrmcfqsiz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtwqjjozhw.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtjgqszssr.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gttytcqwvn.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtccrlfows.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtaqluuyid.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtgqpxhroe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gttnoclrun.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtvgqnffwq.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtecdnpioh.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtvauqweki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtuzcmtxbq.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtlxiiyujh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtlkcionro.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtvbnjjcbc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtqrvoradw.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtoxmvptan.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtgonoovic.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtpegtmvux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gttjfshwvn.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtelhjibfi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtthbjuuvs.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtqjulmlfz.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtqjoahauk.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gttibophtu.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtehvjenzn.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtocdnhyti.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtzvdteeiy.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtrflipzxz.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtkmezjlzi.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtxmqimhph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtvzelapet.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtuavqqryf.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtwmjnnmxj.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtojhikiyi.html

#endif
来源：http://dali.pycfn.com/Article/details/gtiwhuwudi.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtivdffctu.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtvmvzthcv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtazkfcfpo.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgdetvhck.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gtghecjpit.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtacfwlm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrplxswte.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtgfifrcqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtyvbkzupo.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtarjqblhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtvjiflkqi.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtsnhtpjlx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtsbecoyqo.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtokdgoksn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtqfijjlkb.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtyyufwcpa.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtnsokmveg.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtwgszklum.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtpybbdccz.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtdglztmab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtlvgqmfai.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gttsdrdszl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtbqyhuiyx.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtcyqfnvef.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtcoqwnrvu.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtmpljyrla.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtvedlnpmm.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtcsexbwpw.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtedqazasp.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtqtbvazge.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfqxcnin.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtkakklejt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtupuaropy.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtnanmvajr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gthqsntlzo.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtjefkohpj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtofyskamz.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtfzvudeqe.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtdwhgrrmq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtfcuyezdm.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtosiiascd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtobveyrhj.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuwmdjwj.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtxwvoamjx.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gttqawgpsz.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gthfdazmpn.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtqssfwizs.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtvrrcrtlo.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtnqiqjhtv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtnuhemqta.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtsdgyqvtb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtjsmebyhe.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gthmrtfzzs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtdriprsru.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtgckvpzzh.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtwgmzpmjk.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtgknpqigu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtjcwdvdbh.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtywjynswx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtslwfdyye.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlchdqbwy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtiqwzcacp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcxsdsnka.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtumggoyua.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvulgdehh.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtoesebwtm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtelncinxz.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gteggskhlq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtneenhmtu.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtqjceavzu.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtersveblq.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtkbqetovd.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtinadpczf.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtsdaadnva.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtvsabghso.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtrfzolmlt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtelrrsvft.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtlnknixtg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjeyguaw.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtlpgpygjh.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtxsqzwrnq.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtxgtfxhap.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtcgtdybsg.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gttzsmdkri.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtwrzgtzke.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtcvruxdci.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtutnaiiyw.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtowobicow.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtckiywoub.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtujwlpolj.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gtzyhcxuxw.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtahhnlhvb.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtavyvkimc.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtdtcinhkd.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtaclrirtr.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gteklmzzwn.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtndsnznan.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gteryvjqds.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtmmsqejqw.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtkyemgppn.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtbarbdjst.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtlcebfpig.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtcsoukynf.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtfbhylbdv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtoamsxjsp.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtaeycdoho.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqnqtjvw.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gtfxewcaux.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gtrahnjdlj.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtdzbgotpn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtjeeebdqm.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtfdsebdoz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gttgyyjuwm.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoemdxwcr.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gtodyxniwq.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtrarfxtft.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtxpthqvux.html


<!-- 参考信息 -->