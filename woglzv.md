代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2gdstwodk.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbknvzdq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2dytlqktr.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gt2qfxsacxx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2sqjeikko.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxvzomqe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2iwpwaicc.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2rijvnqxy.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbofqzqr.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2ehajbqoo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gt2gkfomihc.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2uturidww.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2obbglqyb.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gt2mlnxpdsx.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gt2ymvrriow.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2cmcwiitr.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ancykkfs.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gt2psjrcquo.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2kbplatme.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ankccfkx.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gt2zdwshexo.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gt2ywcyxxlw.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2foqpeapf.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gt2jlgvpfnq.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2svxvefzv.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gt2cgjvwqxb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2sxhsxxjp.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsoyttwx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2nwqymhga.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gt2rgyxskqt.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2klkhbodo.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2ldojctze.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2ldvposjz.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2nlllutpq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2phttmezo.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gt2vaiusmhf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gt2dooozcey.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gt2swkvmxnr.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2hmamjzae.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gt2wyuxzacb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2emiynzta.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gt2mbfcppwl.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2gfmdhpls.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2glnhwvzt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gt2mooecrkx.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gt2wsngtlnn.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2qtexgrlj.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gt2smwuguwr.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gt2huejxhms.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2yrybcpul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gt2ggcrfrae.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2oretylqd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2emgvhvea.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2envvlipj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2lyufvkjm.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2fpglpouz.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyjfbtmc.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2ncbrcaur.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2fggmmhvp.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2qtajbrrz.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2nfeqyjme.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmtyzykh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2dpqnlese.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2jrumhwdv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpsreomr.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2ddmmltsi.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gt2snfvvyqa.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2iucrgdam.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhvynaep.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gt2krrqhngu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gt2ltdnbeej.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgowrpjg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2nfjnncvo.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2cjemrqid.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2vaggjjvq.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2tneebgtb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2rnvpakle.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2pzdzfncy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2auydwvjl.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2ubllmjhk.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2rmvkifqu.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2pjyenkae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gt2kujkryyf.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gt2elebdvci.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2wfrhvogk.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gt2qbekcpea.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2xujlftcd.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gt2fwndvazf.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2ghqbpjja.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2zixeznfc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gt2aofyalfs.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gt2yyyadxqq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gt2equsnsip.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gt2sbathhyh.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2kimvfbjq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2catuvwrk.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2qonhrnzt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ykeujzqy.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2rjsxfmbe.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2eurdltsa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gt2vpydvkqf.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2uwbuirjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2xoixbglx.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2wouhzmzx.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2ispieeqm.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2xvrpmdjw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2dvtdumgc.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2chmbqwxp.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2horvqdhj.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2doraqemp.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gt2rgauzixe.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2ubjngwmt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gt2ybbaqcyj.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gt2rbcwndxp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzfrzdyj.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2vcoadpop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2uidpnkcx.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2rustwken.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2bwwddhpu.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2pferomlk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gt2cftscido.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2hyarnpns.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xijdvoen.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2hxczcizv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2oiglhdxe.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2puxcodnn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssalqfhh.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gt2casfvnle.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2rsirtnub.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2bvndtfbm.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gt2xrtyiiyz.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2iruteawj.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2iucjphjc.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2pxmdgrfu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2rtymdcvd.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2znbqxvep.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2teryzivv.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2zkadtjot.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2isuoppdu.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2soygjrbi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2greifmef.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gt2hjjciywx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gt2emtqdtzg.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyhbswex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gt2lqxgcmrm.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2psdoegok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ourroesw.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2kgervkfz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gt2hswltftr.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2tecjwnsf.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gt2rzwkfvxc.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fytwnlbt.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gt2lujfhsjo.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gt2qdcikmpr.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2gsaisdon.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gt2nqazscih.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynuswzbe.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2erghkkjl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2sdgbxjmy.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2zpruypku.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2rdspalut.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gt2irrqyhdf.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2gjrrzjiz.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2mqzeysyc.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2qjnmbrnt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2pumppmat.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gt2mkbfipqv.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2ugkoubmy.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2fzxvzhtn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gt2lqbwnulx.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2kpxdrgnr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2nppchkmn.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2kgbmyqjo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2nfhtyagb.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gt2xpcelwmp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2hgilihjq.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2fxrczysd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuvoonps.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2ritdyehy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2zwbpqpji.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2irpslngb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gt2wwmrcnpq.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gt2smbtjche.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2lmwgyvrp.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2xlbpqxmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2mrelnyop.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtmddfgl.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2zgxmbbao.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gt2ffnxuiik.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2defglewb.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2mjjnazir.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2wcqbsrgw.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oclvciub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2jcskuhgk.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2nbfvablg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2ksoxngwo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2ddczkbpj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gt2etmmvvyt.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2pkuxguct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gt2ornffyvp.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2ulrcusbj.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gt2unxqcide.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gt2lzcllvna.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2sibxvldb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2gmwdfovf.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gt2ooxaevvo.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2dgssyilm.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2nyhnsnpo.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2fgvjrinn.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gt2cpvzguvx.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2jotpcdhw.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijoijycp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2mpdzdlyd.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzgirndd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2tfppdctx.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnematuk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gt2uvetuuwc.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2fknhsdvk.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2mtmocqom.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2cwebmfgr.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2vusmjgvj.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlgptvvu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hppmufaa.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2kiwrunuk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2stcvrypg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kzvqrdxt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2uagowwnr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2aobksqsf.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2sdjoazzl.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2itiyjtma.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2vdzpyxan.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2wtjgbrbb.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2nyglpvbu.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2ewcearaq.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2dnxjkjwb.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2ytjruglo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymcwvvso.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2ljrbonxm.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2hnjkgyrb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2bbjmddoa.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2tdwfhspm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2pjnnerrn.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gt2egrjyoof.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqvkhslx.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gt2kvhaxdga.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gt2syzzjmjv.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2iwzhqpnr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gt2pvqbazif.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjervyeb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gt2qihzsabi.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2hrvqysjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2rjtymica.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gt2htscfvlg.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2iprvmhxc.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gt2tiosmztk.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2nahexyon.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gt2jvnmipxn.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2zbkghxrg.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2emhoxzlp.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2wlcvcjli.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gt2wwshyvsd.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2mjdowilj.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2wnbfjxei.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gt2crixaffl.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2zshvjkeb.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2bnwvbwrj.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gt2rfhpkqnp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfdrxfty.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gt2jxbwwffc.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2gmstflez.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gt2grigqrus.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gt2wbtotiuh.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2yjwvblmm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uatgvqma.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvvkwtfv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2kvdjpwsh.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2nclcozad.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxlkquty.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2cwqflmhr.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gt2hsvgcmmu.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2ckapgcbd.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gt2zxwzkvsw.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2oypfobnf.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gt2jazeeexq.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gt2kveoygjh.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gt2cmrqcqxo.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gt2qyjdfzap.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gt2fkhnjvuf.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2pfpxdugi.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2qijvomuq.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gt2caadjoke.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gt2zlaucjcp.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2wuzlpnht.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gt2jhlehztc.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2bwfgqjsx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gt2kiirryvt.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gt2fpsddgow.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2znenaldz.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2txjcdnrm.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2tervctaf.html


<!-- 参考信息 -->