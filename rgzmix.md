代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsphfyoq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtwldzztsv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtoblcwaoy.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtnfkklrft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtyepmouuf.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtbpaapqjj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtsikggwts.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtjitzwdgf.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmcvxxyi.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtloigzqqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtnmamllgm.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtpccurmky.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmkwfsdk.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtvzstudyn.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtxtwtveug.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtnqtlmcjz.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtbxjgrgpq.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtwovmchsm.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtnfrdiawu.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtzlpjylyb.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtfzyhhvrf.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtoyqtgtkm.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtocmkoyid.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtoyxgxszc.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtoiroovlj.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtnvlntzrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gthmbxtpjv.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdckfonmj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtdrxaiqdy.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtrhcekzqa.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtgyobqwdf.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfoubgft.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gtcmordqzc.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtxuoixypw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtnskpgaqh.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtbkkdykje.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtzhpyaswb.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtdjvsbtwd.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtjeojqcbb.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtxxwzdezm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtnyrfkxml.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtjvemodqj.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtbqjgkxer.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtcpbnldch.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtggfhkqhq.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjzaptka.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtoszkrrim.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtcfynjvro.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtzyrfozpp.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtizqgmzog.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtbtxvtnln.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gthwagwaik.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtkrhulwcq.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtywwonkib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtqpmdqwbz.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtqbapozys.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyoxyfap.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhyjdwim.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtvjydxllx.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtjnnmnjnq.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtkrdlvhpt.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gtiagncmou.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtcxyfedlr.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtwrsxvtab.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtxeahfdom.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gttrlboaqw.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtfjkkaimy.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtewbhhyuy.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtvnkfgfyj.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtnsbhnyif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtecixqkif.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtjfbpieqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtapjtxykk.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtpfkmvncr.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gthwqsqzyb.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtbswncmrz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtmsfziqsj.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtcvbwbryr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlpsfjkzi.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtuuqfhisj.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gthnlpqtdh.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtgfirfwcw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtpneuftft.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtuhsksfqo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtgaurwrkn.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtvzgbqrrg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gteboiwcud.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtwzehjkka.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtjrkksmxo.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtkcjrjbrp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtufesyrvq.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtvfubknag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtrrpqtjzj.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gttkjhjlqy.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtjanohcrk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyspsyphh.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtkmhwpogv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtocgwukxm.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtkmlarorg.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gthlnfcqzu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtokuwdtfn.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gthcnmtjyn.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtijnpbgdd.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtabruxjvi.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtnidpuuzb.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtuvriwwgt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gthnkkjlra.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygqfwczu.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gthmgzurkm.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtfgngpstb.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtfasqxbba.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtyoeyafao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdczsbrbt.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtcjyaekel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gtxajxmpyd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtocpfssaz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtigjsnblg.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtonihzfbw.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtnodfnyhf.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgrxxfdv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtuhpcyhpu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gtknbpplvu.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtmlaehkxo.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsbhthptv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtmuerialj.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtpsvornvk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtumpwxesd.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtixyouxow.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtxcbjxcoh.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtieedzmrq.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtyuwtkvrd.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtwjxwtula.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtltaprjwd.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtxwncxxbv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtnukoujta.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezcvlfz.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtfpsflrpc.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtmgrfvruy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtzxfiifog.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtzdznoqxn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkxolaxh.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtipgxrctm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtliercyys.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtyjnyntsw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnnatplx.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gthwksklfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhzryjsx.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpcvyvtc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtrwgpqrxd.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtckwpaufm.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtkmdcokka.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtrnvbaarr.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtubpyduzg.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtxdvcenxo.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuckbkwwa.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtljdczdfs.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtgcojagsg.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtqycfzudx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gthcvsceaz.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtstavwvde.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtsokfsnev.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtcipgjuvq.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtvvbtvnce.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtufzutyrp.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtdjkhuwih.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtwkenjcru.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtjxkwtskj.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtgzkhrgwe.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhgqmhew.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtlgqibtnj.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gttcdthidt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtphqtfuim.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtelcqclhr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtcfdgoiei.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtzhawmjlr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtzcobmgdy.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtvoqkelsd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtodatvjws.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtctplmhid.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtdsrxvxtl.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtswdbuegc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtbudbmuwg.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtgnmtbceh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmaemqzt.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtjtcscttv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtsjxdknca.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtktjvgfnv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtloxtuesa.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtjlsixwqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtxnmqzdox.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiebhbxd.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtejfxxuvd.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtxgccbrau.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtgqsxcfzc.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtqkspbrkn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtcchbmvtr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtxhhigond.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtmcbgctqt.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyseqggy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gthtcfzohg.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtagtszdeh.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtuttaiiaa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtmzcsrygt.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtnomruwrr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtgvpbgzlc.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtakznzbpq.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtxrawtxrl.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtyzntvqnm.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtmmucqpfc.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtqyupzhce.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtklxjgyxf.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtmagqzzjx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtljwfdmle.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtoobpviys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtcasfmydm.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtqswxrfmc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtbozqcupg.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtaestuurn.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtjhzyalno.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtftridrnz.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gthkrjlbmf.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtvviahbrq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnahxtwtb.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqxcmpes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgytdjai.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuhlkmcve.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtzxgyquei.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrjzdchpl.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtzrlhzitu.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtztvzyrhj.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtiyrnxtul.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtscmnipvq.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtrmrjnqyr.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gttbfzdeox.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtfkegdyoe.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gteogjfyva.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtyxmoxfhu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gttuezdamg.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtjebgxpdt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtyoohhdmb.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtxmwgysxg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gterozsvvm.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtuspdnnrp.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtozfrlamd.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gttjrhyxbs.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtkdmyytsn.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtuvmaozob.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtpvvivdqy.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtvhfyozfb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrejfnfwf.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtxknazyrw.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtngwniyer.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gttnvxcxjc.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtittzdotg.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gttgflvzct.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtonsaduoo.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtczwxhhfi.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtdadljfcb.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtgtmqhetz.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtziwupxtw.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkzjfpwl.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpyycuwc.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtnusfuiih.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtlsawvhmw.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtbfnnfzhm.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqloyldxc.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtkrpwbyeu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtsnqjoaam.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtvrghnngk.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtqngqbyqd.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtovpcgdko.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtczqudsbt.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtkxxygeag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtqsizyjkn.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjefnggdt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtvnroydfq.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtpvnssrnt.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtqjmbjila.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gtqeznisaj.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtqpykslsk.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gthelpfnja.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtxvunvtio.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtylrkldve.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtvxwzrhis.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtrjtfxxqw.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtgdjfxvgv.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtntcmkjsl.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtchadiugb.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtisqlonss.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtntdxnmwo.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtatkqzmsj.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlcyuoyg.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtgxmbswoe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtbboyokjm.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtxnqgortl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gtmiuzgcwr.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gtqotskfou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtsmnxpyxb.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtpxqqmzwp.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtvxwcadlv.html


<!-- 参考信息 -->