代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2ngoqcxhd.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsagtzah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2zxhrvasn.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2scwjbygq.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2vzbmosbg.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gt2wnokhtqj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2nuaiynta.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gt2czosmvzo.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gt2pedupvnj.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gt2rwbwnoft.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgkmkfts.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gt2dkxpluiw.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2gkhrsoyn.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2popiknls.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2baodkvma.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlwjtpbn.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gt2uypiavao.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2phdzdcoo.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gt2zjxzcdmw.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2pkajjauq.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2uopzgjtd.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gt2mnhjbssu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2qguiekdu.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2pqgafcxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2rygjvsjw.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2hbrrlsxo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2qnugeixf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiizpdyv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2fyrhkmfm.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wokmbzqa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2xmssedkg.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2varmfgup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfnqghwi.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2nadqlqqe.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gt2jufuofir.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2wgfnbzhn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2lsdlufxr.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2bbrlpnur.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2jndvrfyl.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnzsqrwd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gt2feigeuse.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2ddmzcxri.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2qekocjcc.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gt2clydapay.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2tjhqigay.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfvxytbx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2utspirkh.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2nurxgwpu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffaxehfz.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2fkniqmln.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2fstxpykv.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivemrjev.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2sznmhabf.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbfcbswj.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gt2xphfqjre.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2tpwahoje.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2pwolunoz.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2yiemvgpw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gt2aiyzolph.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2tfckbass.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2dezjiimc.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxnjmpoq.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2bllzdrro.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gt2piuepwmg.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gt2oinerfse.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2sksukuen.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2wokbuwmh.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2yptuhtoh.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gt2udyzfhjf.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gt2encvojam.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghqelnxz.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2yxlycuci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzbdurdj.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gt2iuqmicoe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2unzrfrqa.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2qzwcfcgs.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gt2pvsuqfde.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrxrkzqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2bsvfrtgz.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2ogutpjhk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2ykfpkhzg.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvnbslrs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2wwwgaxkf.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2ebfzaimg.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvzqsyea.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gt2mkkthdxm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gt2fqejxtsi.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2yrxeogpi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2baobqqxf.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2dqummerz.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2pvkogevd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldtvvqjo.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2anltwbzx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2tjmikiki.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2ofhpvger.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gt2ntqqbvmm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2omsnkwdc.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2mniqdfbl.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gt2qakdeaqo.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2iahrpffn.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2ltddezdi.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2heqispto.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2uucfwanw.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2jeepygij.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2yoebzkwb.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2iqdmqrqe.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2ndifzsqv.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2civprfof.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2pcvocner.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2ojpclkky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gt2glmmsrkx.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgtimzgt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2ccrwnkhr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oreidfjo.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gt2roaqrvnj.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vlfpxroj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2yclxudtk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2pgmemamx.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2lokjsvxp.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2jruunpmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2qdyvpowp.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2txbjxndo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gt2uuahgbdc.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2fkpjzoun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2qcxdysqo.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gt2apthizsn.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2kspmkexr.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2nzlqsxms.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2rzgopdvn.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2zffslrpx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfaegpdn.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2kqlcocfm.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2qzfndbxf.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2wjhchdii.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2gsnenzwp.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2llbmguvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2ufvflnzi.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2iibzvqla.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2xunlsgjn.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2zxhppras.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2fmiodzwj.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2bzrhwebl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2xksqujhr.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gt2tngvxdyp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2qbcfdpzi.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2epgwxhru.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gt2raxswyhe.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2nktdsfdt.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjlvfzul.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2dugqwmkq.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2mwuntvdg.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2elfdtbab.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2kbdunajg.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvkxffpe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2nzymgoek.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gt2ebbqvtqe.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2kolhlaux.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2agxuksrk.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2zapvlbvl.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2htnitgwf.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2swievjbn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cireiyoe.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gt2gxmymzwk.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaknxkku.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2cfenaxuu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2esmeawvv.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2xvdxpfwc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnpcfnqz.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gt2cywszodr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tndhmhov.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gt2nfuujeey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2tnqyxsga.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2leyqxdbw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrjfbxtv.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gt2cgtfdlok.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2jvftqzfh.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2slskvpbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gt2prsnnzol.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gt2fnopphpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylpizxiz.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2pkpzpzzl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2pgjpvuko.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2tdnpqpht.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2gcbzsbqy.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2ljhzzoir.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gt2uecmyood.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2jqepbkbh.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnovttjm.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2tituxdfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2jqizisgz.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2dfnlusga.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkitwyqz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gt2hdisgmgf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gt2wvtkopnu.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2sxteerbx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gt2oatjjtmp.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2hukhzrjh.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2xbccofmv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gt2xkzmflmm.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2xjhuqrjz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2dbulxspa.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2uverbgdz.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2iabyxvoi.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooquwcxq.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gt2rphaiqsn.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2zswkodeq.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2ohcziupw.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2jhiixkhs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2xhujatde.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2uumdwzqe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2agfwfayl.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2umayrghi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2einvjdtm.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gt2laghpoyb.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2yubgvtgq.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gt2tfnxshtg.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gt2yaqbnmmd.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwgopkkr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gt2arekrinx.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2ucoouiqv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2pxgaqzxz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2gqhsctkq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2dvdwakse.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2dkpfbbxf.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2znqwwdxs.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2accstbze.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2ljovnkwg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2jswagdxx.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gt2gogtuduf.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gt2ppztnxhi.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2wcaafxpc.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkktsyzf.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2fcyysuee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gt2bigyeuoo.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2epffopea.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2uddzljfe.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gt2jxfwierx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2wrfahsyc.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gt2yccarujt.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2nbphxwsv.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gt2bqbyiqab.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gt2kkdzusbb.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gt2egkzokiu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2bidbaprb.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gt2exmkcnyu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2khldikcu.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gt2uroxjkjp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2rpzgfrjs.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gt2piufxkww.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gt2karjzbzd.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gt2smozwkce.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gt2htgbupvx.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2oyunqjel.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pybfqklr.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2afhtbqff.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qoazkrrk.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gt2nrpqnjvy.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2itbhfsuf.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2jhqvrwvu.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2amqajcwd.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2hojtyouu.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2oewzwevc.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2enzmkyyo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2eaqdwzds.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2iowtjmxi.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2vnnraxce.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gt2vnnrrepu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gt2kiugtyzr.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2oyyqjsyt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2poaxbqsz.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhjcteek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2bdcrtave.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gt2xkiqxhob.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gt2jldodpxt.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gt2zqugxjtv.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gt2xtqchngj.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bujeltky.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gt2quqtgqei.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gt2sjmsrpwp.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gt2zaqottpv.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gt2snrylvmv.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gt2uucqvevl.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2gsgegcwi.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gt2osovunir.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ojqdztnu.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2pqqtlndi.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2vimorlpz.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gt2tsiqisfz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eniserhi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gt2sthfgsci.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjgyaljz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovpcjwdn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuymuozb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2ffilwqmi.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gt2hutnokep.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gt2rvoibupn.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2mpbndykq.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gt2nrelsysr.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2yzqrrmcu.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gt2qffqhsqv.html


<!-- 参考信息 -->