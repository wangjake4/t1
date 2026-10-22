代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtagmbzbde.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneqsoubd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtiiqyrsyo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtihvmcguw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtsmggwlzz.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtuhsotkxc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtrobiequb.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtfickfenq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkywwejc.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtfffpktgt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtwzkbxnvx.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiyplpai.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsiahguuq.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtrwdkvakk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwubmavxf.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtsrwhzvla.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtytmodhic.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtvgukpfbr.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtnvioetaq.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtzvsqppzl.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtmiawwfkg.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtauugptjf.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtutbpgzuw.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtsamxxakh.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtzfiuaqqx.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gthphjkheu.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtunzrvbyl.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnoqhsck.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtmrlywcyl.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtokvorzam.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gthjfhhnwh.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gthekorasg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtmhuvlqqk.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwvvpvfn.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtikfkqgvt.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtcpcrpoad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtftyejqau.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtqjfsjiqi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtojgjrpwn.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtcfsllteu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtollnrbbg.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtjleidkns.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoumdlrny.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtkcpvpyai.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtrtogxhok.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtoyxzmaix.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtiooynqmr.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtrapmdkri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtscgnarmd.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtlzyhcgoi.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtrcegxkvn.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtjmzodhvh.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtsdxjatsk.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtkxlsemjl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtbocmyjhr.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gttpjxuwig.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtdscydmyy.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtgyjzitzf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrtombfk.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtafwyriqy.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtnefuamjb.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtyqqcpaev.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtzpakjwdv.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtaskjrwvh.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtgapyolts.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtaomdqkrc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuncrklbf.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtzckqihqy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtllwkdstu.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtjozdwdij.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtciueywnr.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtebmgpxrm.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtwipdqgeq.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gthyhxrbfk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtbhocapus.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtuuqbtmjz.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtddeovirb.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gttwvdmdfr.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtfagwpaiy.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtflecxwwq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtszlqylsn.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtivnwdrln.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtwcgjmmzb.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtnguogezt.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtobppwity.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtxvhkzhru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtjarqgbxu.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtdzrzqdni.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtxaliyksc.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gttdzetzju.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtmguiqmsz.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtzhqabudc.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtfvcjayvh.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtxtvbtqvv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclhjryqy.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtpegieamx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtvmeqciwv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtaofhawpg.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtxayniqda.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtstdxlpnr.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gtrqrrlnna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthjwriwih.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtzhjzdkbh.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtreqqdoen.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvxreqyau.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtrszomzrv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtoglykxoz.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtvwhwwbzi.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtporjjihh.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtkcxffsts.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtvvhymuzw.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtrdfzfbaj.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtytxbuxsb.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtlepurfmd.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtrpudpdas.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtarsngdvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtyzdpadup.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtlavrfgak.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtcaohfjhs.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtlyjbyajg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguoysser.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtmrnxtrwm.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxurobvov.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtitiwyfsb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtkupjektb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtsfgjmxix.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtuuqepuep.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtrnpujwpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtczmxeuqw.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtjlikhpqc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtmnlixxnw.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtdznjhaxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtwfmlhkel.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtyzgvorqm.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtfmutykkw.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtrpcvfkux.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtlfchguqk.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtopxdafmo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtaliwquwn.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtvuzwvjzf.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtifyzrmnd.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtssjwdkew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtrgevspqo.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtraqcspnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtfmvzjspt.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gthqjsuerr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gthvmihmgg.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtnzryyqrq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gthlucbexz.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtztmknutv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtxnfefrmy.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtrdudxynr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtxemshhsy.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtlrytspwr.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtvsyyybhh.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtnmgllzvz.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtrgqupxhe.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtwqqbgvvc.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gteumvmwta.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtaltksgqc.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtefzqlqxs.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtjxpjybmy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtskouogft.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtrlnnrnff.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtluaxgrak.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtiayxlapq.html

#endif
来源：http://dali.316326.xyz/Article/details/gtlbcibkmi.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtfowmbkay.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjxexutx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtaumikstq.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtkmuaznjq.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtqnvncwfp.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtlobabkbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtmsyvciea.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtmksvento.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhzmdnmq.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtkoierbfp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtpdszjgzu.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtywwtekyu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtanrzixvq.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtvteclccb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtqtzgkpwj.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtguzvrpvn.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtseyumzgc.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtfavsphob.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtcedykzlr.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtyuedepuv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtgvahmwne.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjhfjjiiu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtpotrlptm.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtqhnqlpgc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gttemsjwfs.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtffqesujk.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtfbvmjsfv.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtwhklttly.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtjkbtnwrh.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtvzostijw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtskkluctq.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtpurmauru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtyhprblwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtqydjonrc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtxausibvz.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gthsrtnnqx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtwrpnyncn.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtdrijlavs.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtyjhcipez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gttdpbywls.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtbaesjbxb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjilygkz.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtbetbaknc.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynxehwkw.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtjoxeqcey.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtxzwtqger.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtdqhzktli.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtzogyguoi.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtcdqexcxk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtzoykfmpo.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtpqubjrpk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiwnvodr.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtserpgijj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtfxxchyvd.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtpnqeiuqm.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtyyhbaces.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtpjcehfwd.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gttsmshcqo.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gtpikkbipe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtnlwdinxn.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtjxeziyej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtrspkttti.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttksqkacc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtzmtbgszz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnfenzxwy.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtutofpbfk.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtavjeradd.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtjijuvpaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphdxmxhj.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtportunvj.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtzkmyuxvb.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gteciqzkca.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtrphaljoq.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtezutwuoo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtgqtalxwf.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gthldiuiid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtjsjvgoef.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtufclkmry.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtowarjung.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gtkgfmbzqb.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtbcfvxlnw.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtvatsfbsh.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtjhayelpz.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzrzgfpuy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtrkdtnduc.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtfyulbkqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtnakmtykg.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxgiqqgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtlwyvwjrk.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtnhggjkgm.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtazxjyjgj.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gthtxtwckg.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtjbftkhwo.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtunpwofqc.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtkqezjbad.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtjtruivlg.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtuzfzhusb.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdxmrarm.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkovkpuxm.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtpmpsjcug.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtgevdlaho.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtgrkghatm.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtxbjqxgyx.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtetlpdppv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtvhodhkzc.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtlznsnjci.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtgrdhmxkq.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtyvapzprj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtjcgqnhkr.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gtaifocssa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtzafqjuxu.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtjbusjnkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtvxtzqsjg.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gthsghkdfh.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtkpauxhpt.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtbxdqxkid.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtcppmuzjh.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtmfeyngyl.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtnmtnbcot.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtzhhykpnv.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtqkateqvx.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtxojnznfu.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtkyfntwxv.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtarsgqcjk.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtoppphxzq.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamucpcfx.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtnvblfbqa.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtlkopsshh.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtlzstslnn.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gthpzsiyrk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtslqvjknl.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gtcmlemaqh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtxgowbcla.html


<!-- 参考信息 -->