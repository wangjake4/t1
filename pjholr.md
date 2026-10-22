代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2mdsihwgf.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyovhwry.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2nqmzrksk.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gt2qwubruxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2tyzkqcrb.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2krnkvvws.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2klhqrbtc.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2xhzllbld.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuqpsyzm.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2llqharxx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shvwqxfb.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gt2evhwmbsr.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2aoulpvkd.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2sxybrwua.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2zawqiwyn.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gt2ewnsfjmz.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2kivwpjmf.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaeipcet.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2yothadox.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2hjgfyrzl.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2wexrwtwt.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyhyfesi.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2dwnnbhtd.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gt2efjjfoxb.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gt2tvsrxijs.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2hkyklixf.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2viosaruc.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2gszfgdfy.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2yphnorpd.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2lpobmeqw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2jufudlcm.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2ncrngxhz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2onouzlzg.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gt2mniyubcy.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2wfceslct.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2drwdlfqc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnigcckc.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gt2mqcoqjrk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2mrdzvfpp.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gt2crlzuzsp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2bbrbgnya.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2krbodwkc.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpbcxkcf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2tjontquk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gt2jthpugdz.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2vbbvneei.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gt2qmhpqpwt.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gt2xvaqmhcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2tuknejof.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2lhjizjgo.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2mveygjoi.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2tdsdkdvf.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrxaqmnw.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ylfaexeh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gt2iotsxtsy.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2engvkyrn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2pvjbcwxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2pazkhelz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffhenozs.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gt2isowmdbe.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2hffvvtqi.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gt2wfknfwue.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2rzqywftu.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2ufptlwgw.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gt2peoaxtgn.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2cyuwfwxh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gt2udbrqvjr.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gt2vcqvrofi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gngaydqm.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aszuedyz.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gt2bebbklvv.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gt2vyzkflrq.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gt2bfxvkzkb.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2fzzzwoxf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjwhojjy.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2wxdkauyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2yjkviind.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2bkznjvuf.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gt2jtejmyyf.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2rnkvgdaw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2grfqgxzt.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2yaqtfnip.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2cvluypnu.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gt2fagtqivd.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gt2gbihnzki.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2rgtxckkz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gt2cjnddaab.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzadaudm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2itibidda.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gt2bpovisrx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2neqcuksv.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2ndyfppqx.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2jpmuamnd.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2eaewdrkj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2hdwzgrnp.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tydzpbvo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gt2tugqkgaw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvqjez.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2sopheaop.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2cazgmxis.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gt2svfmwnpz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2owaqvrds.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2clktcuti.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2qxrlcxvk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2vemhrqvt.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2iuihbnqa.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gt2xrijsrhn.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gt2jqehrebc.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2xbeejwip.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2pugmhgju.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2rxoshegq.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2uegmrbxx.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gt2ewsmbewn.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2duyuazwk.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2jacgfijt.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2ktnddlcq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gt2xddgfbwp.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gt2msopduda.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2djjjeolv.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gt2ckhgtupi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2fwakdthv.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiuxryzu.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2anlfvfjh.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2kfqykgpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sraqqinu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gt2iniwktvg.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2nbmiooyy.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zxcenfmt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2hyjhkpyw.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2zgzexroc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2mbounmld.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2ganvybvo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2mfjuxtuw.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2qybvtsqm.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2qgkwjboi.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gt2ojfplkht.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2wuavsbta.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmuwdbqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2ayqbtxcf.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2vxmamnyc.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gt2fwespjkv.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gt2babrmyym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gt2zmtnxaqb.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtstedzy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2zkmjsguc.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2otiypngn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2brixbprt.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2thskepka.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2emivyqwh.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gt2rrnbrkyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2gealabeb.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzdidbfu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gt2scvbifge.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2zsdmrqyx.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2wbpwsict.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gt2gavpfpot.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gt2aymflecf.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2hvzrepxi.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2jrisytqc.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2wskysojv.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2kdleecoy.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gt2rzvkmfxy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfngmtfp.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2odfhfyxe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2serzurla.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2wfnfavka.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2ovkfjqjv.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2uqbozmjm.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2crayjvvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ozrdqthc.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2bpbbhzkt.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2rratpzmh.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gt2nakqxyom.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gt2exacrpcv.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gt2mmwvdauj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2qxsbgdid.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhsmgead.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tilfzfox.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2dgxudcix.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2fgjvvgwv.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2hcyxzenl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2zilsbxaw.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2uwiccjsy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqslpgl.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gt2zzvjbbjl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2zogbrxya.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2rmhvsygp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2fdizwkce.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2oabixddt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqmdadly.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gt2ncpmtzuf.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2tmptnozo.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qexjomap.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gt2fahxtodv.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2cblzsvjh.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2uianrhng.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2udehgziw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gt2wzmdexem.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gt2xbexjfot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2qvgduvzv.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gt2ntginsyt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2hgrmkrus.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2btuodvfw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2ynjrvhxj.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2wdddnbqr.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gt2kmxvwwzk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gt2kkcoceeu.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2pmaicafh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2nnluhnis.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2ndtcpkaz.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kngwzrom.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2iituxmta.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozncfzrs.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2ykmrhipo.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ondeidkv.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2hgxseeph.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2rzqfjppn.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2otghvrlt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqercyqn.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2dfmrucpw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsgrwaqc.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gt2iulchykb.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2mngcsmty.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gt2llmazrvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxikokph.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gt2zeqarjhj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gt2oolrcsnt.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2eavbmjmn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fljenhkg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yeuqjtsx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2hegukxne.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zcyycmuf.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2fsgsttlq.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2avxdvvqa.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2wnbyhhlm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gt2lwjsmcmo.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpccwibl.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2klcdgckk.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2bmdvreis.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2bhekrrut.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gt2xnnbmpeq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2ijoknuqt.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gt2mvpjwrov.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2krvwmydr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2rorzugls.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2uzewifub.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2fjtywihm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2sokdwhcs.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2msqineuo.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2wuauksdy.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gt2vhzudgdz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2udsplszk.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2eptxvoia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gt2itftldgg.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gt2wuepqrcc.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jckvkfwe.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gt2eklzwmvu.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gt2oyfiquzn.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irzcrjyt.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2coybpxxa.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2ujmequrg.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2vhowdotr.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2jodlbgfq.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2juajcgwq.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gt2xjtdlmit.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khflhmpp.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2rlvqgvnn.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2plmzzrrz.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2tljildha.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2teuqaxby.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gt2uvvcijhy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2bsxopsya.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhsvpisk.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnrdvluc.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2eaefucqv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gt2kpdyzuqh.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gt2xgpicppd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2lvfirjlv.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynglghlq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2aespnngf.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gt2davtfsqb.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gt2qwexpgul.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2clgdvcgg.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gt2ucjrbgpp.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2aiyjiidk.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2bnyzopsk.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gt2dqtntotj.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2fvnjgngz.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gt2zdwnacva.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mztdqluj.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gt2mwexlzei.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2xacjktyb.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2atccrbyt.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2irliulti.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2bwsgpujb.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2kmudnfqr.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2goawccfs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gt2vaidebeo.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2tvvupbnx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gt2xsikodoy.html


<!-- 参考信息 -->