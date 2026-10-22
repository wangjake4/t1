代发 wailian999

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gt2sfxavpoe.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2hccsazcs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2geponwto.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gt2wucrypjd.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2qndrexvi.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gt2bikoqvcl.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilwxxegz.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2sehulowf.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2myalrifd.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gt2xstsiezp.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2kgxfxlpk.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2zeockukk.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2nhnuwfdo.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gt2xzxbsaah.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2cplrrwto.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2ayefmdmh.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2glcdrdyg.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2zubqmgcz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2lbxxfyaa.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2nbujhzba.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbzuixu.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gt2ukhvceee.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2yqifgsnv.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gt2igqndfjc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2raslitur.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2xswtnevz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2hnqkkcrv.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmotpzdr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2odpwtrsa.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2zydonbdr.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziaajqiz.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2bgoomshi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cowxtwhr.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pxpcevft.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwhvsstp.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2qmisdcdt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gt2whpqzmqc.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2ppxzxjhl.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2ndacjjym.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gt2qyevjwyx.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gt2sxwpxgqd.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2pahgztvl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxqwkina.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2zvmrhnsr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2ojitdgrn.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2blkviuuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2ivqmvxqb.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gt2kjkmkahm.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyfnpqoq.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2aaviuovi.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gt2wfezvnjj.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gt2tsxtipyo.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gt2uatcqlno.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gt2iznmuece.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2otvytghl.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2ldgzhyvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxlceggv.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2rwiclesh.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2gutizjov.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2keadodgu.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gt2qtowtkbh.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gt2dfpbblxl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2bbdeftji.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2lksivxii.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2xmtwxgnt.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2vtwpibdb.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gt2yimcujom.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2bczrairu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2qpsrbwgy.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2jkalepwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2bhvjbjuo.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gt2xfjfnlhg.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2aolbgaep.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gt2szkxpgri.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2cmnpnvbe.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2duzraprh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwpityrc.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2eyskrqbe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2gezntiax.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gt2kggjuxnx.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2keembibo.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gt2bcjxbero.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gt2nodixcdm.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2gcgqkybf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gt2nxwyqbqt.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkszrjvw.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gt2thhyceox.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2delgtbqs.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2qippfoum.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2casfelyj.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2uscobnnj.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2xpreyobf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gt2oqquusas.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2odzkdxzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipghhlwf.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghqjbfym.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gt2qtvdnfin.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gt2ywavehgl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2znnhxulj.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2qdkjylev.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2rktdkstr.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2cyrxsxio.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gt2owajtemm.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gt2kllbureu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2kwlsjodg.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2unhgmigq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2jpdfemfz.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2itwrvjna.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxzabmmo.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrsrxgup.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2gpfajvky.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2ixqkblan.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2dyfhjkdv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gt2vfvmiifv.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2mwknjpuq.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2blwxdngb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2olievzou.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2knbceylw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2ctdbglha.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2fkgsyfbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffurkwky.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2xjupomtt.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2yawpbloo.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gt2xlafbzkt.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gt2anoyixoc.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2mdzbdamf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gt2ywabtcvi.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2cedabguj.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fexzcwfw.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2legdbeue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsajhvzj.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gt2wphpfxqd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2oadkycmp.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2zqoukkyz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gt2bslkxlpi.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvxpcxko.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2cgwzxedp.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2ywusgyyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gt2ricqjgmg.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2tbsdlcaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2ajrvnspe.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gt2bytxwrdc.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gt2gqhyhzvf.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gt2xkdgfqqb.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfjtfvvo.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2togobick.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2gzkbisrp.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gt2vzvmwplx.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gt2qifavcug.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2ftfbpqrc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2pposuhtc.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gt2oucqbwyw.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gt2kktgvryc.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccfscypv.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gt2kppyvpor.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2iktwoknz.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2trvlfptl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2muucwnux.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2jqcdtlkh.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adlxvkpl.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2hqkqmiot.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaaibxut.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2hckeaohq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2uxxrgfdn.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2ppgswhtq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbxogvvr.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2cddnoaeg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2xgqwupgv.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2tsyqrfqi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2rhnfiodo.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2loasovbr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqryyml.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2azenvaei.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gt2vcuxeqvr.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gt2wpymwsix.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xogpakqf.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2bszuwpfd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gt2kfkpmzer.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gt2cxxtbzge.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydjzgsca.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzunklwx.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gt2hsaoeyip.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2zlbdvkdj.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2dumagrzb.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2ntnmubza.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2dgnixosb.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gt2sazcocvf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ywjebsue.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gt2morfcmnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gt2nnkcknzo.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2syckgkzf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2brsgkrvx.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dimcsgii.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2fjshvuni.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gt2ghqtgvwy.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gt2fwcivxlp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2mxcfdzoo.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gt2cxecsuph.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gt2jxjnnbpm.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2ihumatuh.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gt2txofuyno.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2utifhors.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkgrxigq.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2ecrpzbph.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2pbwbmfnp.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2imjfbpgb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2fmopshjf.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2wlpzzzua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gt2fsdqpxtj.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2ofwequya.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gt2diletrco.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2wvddtgww.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2gxhbovrd.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2fakciazb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2rhjhnuad.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2aaofeyaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2hvbdosfh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vcoztrqq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2bypwsjnt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2evftghxq.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2luoxfdqj.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2uheyglkp.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkvghbli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2xybmhnoy.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gt2dpbuhgmp.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lutkkksu.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gt2zuoopaqe.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gt2qoevlecn.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2jsdkziyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywphtpfz.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2ondccnss.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2lijsomux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2pmrkhjbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2gcedzdyi.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gt2acgbsviv.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2iustxwml.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gt2ltskoqax.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2elbabxlm.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgchgudy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2mlejjpmt.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gt2vuftscpg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2mbkssvaq.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2zsyhocnq.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmymhzyv.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2gscdrrwb.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnbgellr.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2xfyqlclx.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2zvizmtry.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2fbtfvjpi.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gt2oqdjmxbm.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2nbtnhalv.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2bxfrtavn.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2ejjhljyr.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgwyxiyd.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2skuvscbk.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2ngbuovuz.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gt2lesxyqrm.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2blkfnbes.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gt2cfitpmxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2zmhnzysb.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2njmowqap.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2lxvyigfv.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2orlvdtcf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjcvifxl.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2jkbrsihm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gt2nrullbwq.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2nyvmedjd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2drnobwbu.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gt2fxsrxlwo.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2ijalutam.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2wndspczj.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhitykof.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytevrmbx.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2caacyoee.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2zindhfkh.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2wnnynwjy.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2hdsuqpsf.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gt2hwxjjuht.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gt2yucqjoof.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2rjfwxpdz.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwkgolkd.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2lhsblhrb.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gt2cktpqtem.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gt2njqjwrvz.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2uswrwgyn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gt2hgfgwnwq.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2nfilwefa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gt2pivdivzl.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2ldnjujpw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2mehirlxp.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gt2rmghmhew.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghkpynea.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2rooayfql.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gt2ugrqmqcx.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2yqtshepj.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gt2ijzcerud.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2hguvryzv.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2fhuacucm.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2ncezftol.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxdtjpfl.html


<!-- 参考信息 -->