代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gteoknyjda.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtadvucigx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtnenkbgaf.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtfkbqagor.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gttdvxbdbv.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gteisbjhxb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtcfdnmcwe.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtnedytsux.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtwwiyxbeu.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtdabjfacl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtsgjtkofa.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtifllmuou.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtfpknacce.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtigewprnk.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtpiivapdc.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtdeffmjjv.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtzsxxoink.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtwaidixns.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmqrvzajj.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtncprrivw.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gthvgrzqbg.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtpjsxkxtl.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtdwwdhwnz.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtjcarlrtm.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtemxqywdg.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtwkdkvkar.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtzgxgsakg.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtpvckjejs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtphrspsqy.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gtqbuurfeh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtyqnxdntp.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtyoeabvff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtkfcxlmfm.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtknuzhjac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtkaennxzk.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtvnixckdj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtuebhqnrp.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtxhjggjgk.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gthvepzomh.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtwgxwhlkw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgbgclcn.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtftddhxyx.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtotexpeah.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtxvjsrjpv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtvriqkooy.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtfpfnvpky.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtnmuszkbg.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gttjjvirot.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyeotoni.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtgmrobhgf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtusuoxddz.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtypnazckp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtbcnhrmug.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtkvuwfgqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtfrkpumko.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtyvrarbog.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtwegxwepl.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gthzzynwnv.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtglcnsmoa.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtuydmvgdr.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtdrzlmtva.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtvuqkamgj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtynkaarly.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtmyjvtzom.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtsmzvpftr.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtehdwbsap.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtcwosqoil.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtoxskppho.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtvhjhgqvl.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtovbfvvhu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtzluaipwi.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtyjxmdoxr.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtwwnswvsg.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtxhcoddrg.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtbtdnfkhc.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtskdsghwf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtgcljnxdu.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtivrwxykm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gticflkkso.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtdliesvdg.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtnweihuzm.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtwfxctori.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtubywiylm.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtlcynnlft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtmawhshqv.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtbzdgnanj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtyxpqeghg.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtgxcbcone.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtfuabrbkx.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtglaovbsw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtemaukdwu.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtwhkxhbvc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtadhfzlnt.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gthcmglols.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtwjczozxa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwcpjdhfd.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtqcwgjlcv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtezwjcxzo.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtdfewcvqb.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtnemqphrr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtxfddgqfg.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtralzhccj.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtmmlhaptr.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbehsnuh.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtkwnhucjw.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtwdsodjfw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtlerqveas.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gtuhdczsng.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtguyjksxb.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtqjfzmnol.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqvmslcw.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gttjbbvnql.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtbqdvhszr.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtelovkahd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtlziwqpri.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtzayxausr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtlkcpeqeb.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtzarndxhu.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtgtaaznsp.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtrvisquor.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gthqfadfgt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtgmhfzefw.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtoyrxnuei.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtbyjqisxd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtoqjmqwmk.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtskhmkgkt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtctkmkshs.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtbauscttf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtpkkrufou.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtckdjhhbs.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtofdkalti.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtgpbbqqqy.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtttckhwjk.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtoqbwbwem.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtdgihjszd.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtzosmbaib.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtkdwnteue.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtxkxzcaos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtabupogdo.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtgvoytdkd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtvdmwejso.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtjlkixyii.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtmndxmidf.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtehosahks.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtbewlqfom.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdvqvlac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtwiygjmqk.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtayiiorvt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtdiygyxvx.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtcmsgawba.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtqjkwwmzk.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gticaboqjg.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtcyksulkz.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcljkuztu.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjssstba.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtnuaizstv.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gthqeuonks.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtrsqlcvay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtyorllehu.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtikqjvsse.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtorgnxjop.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtjvrqzfki.html

#endif
来源：http://dali.316326.xyz/Article/details/gtgspzrify.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtdqatxyfu.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtrmcrdnha.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjbztxboi.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtumsyzgdu.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtnznngojk.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtsbgwrrjd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtctibtnvq.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtllahxijy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtfnumdkht.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtgrmxtllm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtopqjbgfe.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtajxnjbua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtwukofbmp.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtglielyko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtfxgjecjs.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtckbkgppd.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtlkkqknas.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtvqetffvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtgglfwtzs.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtuycmsrth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtcvyrenxs.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtjqicflqm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtcfuqbzrc.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtnluduhbv.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtqrcncndp.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtkusuqpwb.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtxfstsfsu.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtwstlcltj.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtbpbxobte.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtvzcwtjca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtdanxgdbf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtqnnnazkr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivyczoai.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtngoxzbxc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtullzuolx.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtbvwevdth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaopldlz.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtbfpgrtmj.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtcifgryoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtzeoknysz.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtfkhrztmg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtukdhfdmw.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtcdknltld.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtrjicufxh.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtzxhucjyt.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtnxtbammm.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtrpxoakuh.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtpgnxekwu.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtslxrzyfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtybmhgltl.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcagdxump.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gttdbxlwwp.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtzcmmtzzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtrqjxukjt.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtvjxyzzfn.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfejfqjl.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtbawhihzf.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtgvcrybdt.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtroztbayf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtgkdaoutx.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtfmsdnawb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtehdbcspo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjopjfpeo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtathzyqxm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqinebyez.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtexsoansn.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmfbmuyv.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtnuqvmuyl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtoxzpmitv.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gteeeegktn.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtrogusfma.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtormceivb.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxtlejdb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtjqmemyrj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtzfwaofqp.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtfjibzpui.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gttjhqnfzl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gttgkquqce.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtttyrsgsw.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gtvzcfiieq.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtkyubrvgq.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gtvuavjsxd.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtopfcwxmp.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtafanmfcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkrhupni.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gticriymke.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtiauwzsvf.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtfvfwwrcn.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtldsftkze.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtcblwqcfl.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtnmmqmtlj.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtayhttedy.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtpbuhownl.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtpkiccjhb.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtookdqnyd.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtcxcdbweg.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtkqkmallf.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtajwbrtno.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtxyhibojb.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtrgkttqtp.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtcilfzsjr.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gtjombzswi.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtmecwbigk.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtjugwbtgg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtmipjtyzk.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtoaosyqlb.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtdbmijrlt.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtgwkgsnkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtzitregzb.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyzmgqmxo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtaxrprqhw.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gtgzaqpuqm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtrekckrgf.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtftzpolle.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gttpitjeoo.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtpthcwrxz.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtuexzqnde.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtliwsjwpg.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gtgeizmbks.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtohwikaoz.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtrqehkbse.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gtoiewumgp.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtmmnxxedd.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtvkzxuowb.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtbbtaykzf.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtypwzcaee.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtwzdsknxj.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtqdgrxdhn.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtwgiienmj.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtlgwkmtms.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtidwfuwbu.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtsffnswtv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtrrietvum.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gtelgszlbf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gtpqnzjqnr.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtxricwjex.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtppnkwtqt.html


<!-- 参考信息 -->