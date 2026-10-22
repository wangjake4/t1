代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2kzfiyeyh.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2wrdaodup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2wsftvvdn.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gt2vuvwvlbi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2apldtgtx.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2jopnvopy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2wlhsirho.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gt2diufjuxd.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gt2vujjbxos.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2dpuyjchi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2ehhjouhq.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gt2vgidsebe.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2ssrydwdd.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojbgrovh.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2tehafljf.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2xkwyfbew.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2mzkzzmxq.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gt2tuctrvhz.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gt2rwhvhcgd.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2utlowkjs.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gt2bibnjjwy.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2hfsxkegi.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gt2zkxviewq.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqamaqfp.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2htndrhuc.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2nxfibrhw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gt2kcgjytjy.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gt2rxdbzxns.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2nadyexun.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2candwtgb.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2yhldickx.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xigpykqk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbszeige.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2bnrkoday.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zerzboyk.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gt2vrnrponq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gt2jrggevmk.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gt2hmkhgbnx.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eikxagyd.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gt2nzmxjefj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gt2gijfiwhe.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2zhjqvqzf.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gt2yyfbntsv.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2udrklbam.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nyysjois.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsgcactg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zipxwomu.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2mbmvvkfq.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2lwhknamj.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2jvspivpz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2wbihjvca.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gt2ojqyklqe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2ximscptq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuaefksv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gt2nthwvvsg.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2culjxkad.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gt2tozbtxfz.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2vlsxiyih.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gt2nnnhjrkw.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2rgqzqnzk.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gt2ynwbjksc.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gt2lzpmpvzr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2kdjfmstv.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gt2ybmfplpv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gt2loywdfwi.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgeghzeq.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2tphqgrso.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2sxfjxitg.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gt2keziohnw.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2hyxnldqj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btkcuokw.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2uxqfmzcg.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjutxptb.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gt2rhcdhcll.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcfwpunr.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2iodcmoyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2tegznfvr.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2mezvthar.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2ylvnuvme.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gt2xnyzyqcm.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2hmzfmlhr.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2zgtwofgw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gt2cxwtxuix.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gt2jaajujkj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gt2zantofcz.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjbrsuws.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2eusziahr.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gt2dlnvmlxf.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gt2sviublxl.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2fcqnganc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2gycjemda.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gt2xpiaclcg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njidxxqx.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2kddtuuxl.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2vpkjkbxu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zqcmxoua.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpftlliw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2bhrxfcfx.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2dtwnrfhw.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gt2whakcecm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zlnyvjup.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2mimwcicd.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2lhpivrhc.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2hszbcfhr.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldbjgkhz.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2flzapscb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2inepfete.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2zwwfiioy.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2afrtpejr.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwgukkvb.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2ybeuaboj.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2vmhkzyzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gt2fxwlrdcy.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2prowurvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2xqpsnnbw.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gt2ycglbaga.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2stutbrsy.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2mdvjjska.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2sthiyzwi.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2frqenqoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gt2dxiqevgb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scdlxfpk.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2ybifsikj.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2yexshmre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2cnphfwji.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2fvxxeotk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2kqdmumto.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gt2xnukkklv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2ubjggieu.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2vkyamrnu.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2uoqsqkkx.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gt2nkzbyilk.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gt2boaqzrul.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iupxyfdn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2zmnoivsf.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2rpueyrmq.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2cwypblcj.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gt2nxdctvns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayrseozt.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2otubunxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2nrxslmkw.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2efiwbtep.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gt2wxzawppi.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2edfrialu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylubveyn.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2vvylunrb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gt2jxdtwlvh.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2ghczawsp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gt2lljqnshg.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2bdsrheoj.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2xjqyueyp.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2wroslzsk.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2ckqopcrs.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2mnycawws.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2xdolhyvh.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2vucyujxg.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gt2epjireui.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gt2eqfxdsfs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2pkhscrgg.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gt2xxmkcxpb.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2wqznfnfw.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2lwevdmkz.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2xtdowzbt.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2rahjnpql.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryjjdzpb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gt2pteqqtii.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2odkegdtd.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gt2cnfgkiey.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvwkwemw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2nzovdtzj.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gt2xomczjxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbwosjyn.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2rltnzqya.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2wclvabyk.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2rnhnuuou.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktqtpbhv.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2qjxjbvzz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2rroposka.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2kvmgutpg.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2dqntinbm.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gt2snnsinld.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2cnfozqyp.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2rckuunli.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2anatiyor.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gt2gtduxagh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2kyaozlmx.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2dcexdobc.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gt2qnqpoqra.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2umqkfqsa.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2ilyjhvhv.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gt2vmdzqhkj.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gt2iuptefbv.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2ahqcmtgr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2ofjkuylq.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2kxqouoxs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gt2zzdrccak.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2bcetnlbs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2hvlvbtwa.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2cgtgevay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2lrkimtdv.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2mqxqeozm.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gt2pmgfegvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2tfipqeav.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gt2ltzyfkyb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2ftaviakm.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2cxtoigso.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2cittmrgw.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2ksejklxi.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gt2tgiefjqn.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gt2pvuyvzxa.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2dnyjlupm.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gt2uqwrzhfo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voobzqgs.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2bjuoidep.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gt2sawbqbsu.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gt2tsozdmxo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2zccublqp.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2rkgnlaqq.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2piqizqtr.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2zhsmqgwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2lvdxregv.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gt2aoqmsuhn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2ckvbrilq.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2urrtycmu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2haafmeaw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vtygybuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvkgjovg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzyjdghd.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2ewhgeixz.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2xagrxbmt.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2vhmjceqj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2ypslurvg.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2cacxinff.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2xwsibixh.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gt2gvrbuzmt.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2jeftwgdn.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxxwyefd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gt2ubjcbkhg.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2zllovtiw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gt2yeyozyvz.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2kyltotmz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anjjcbme.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2kuuicpjp.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yttgwgst.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gt2jfjtujot.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eknkgkhh.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqrvidzl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2iwdvsbzr.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gt2cfjhldxc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2vduaftuk.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2jhwgjsko.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzlfgti.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gt2zfyutfsk.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gt2jukkywyo.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gt2tfgumlyb.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2wgerrfkw.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkpmalpu.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gt2gzgdyjtf.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttnuyvpf.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2ylfydeea.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gt2rhtlcvoi.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gt2onhcrbwh.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2frvzheep.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gt2fosqmpfs.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2cygekwpa.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gt2vvkuxvfv.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gt2ospnmgjr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2ztlkmmsw.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gt2juvbzugw.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2kvyxzdmt.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwtxhqle.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gt2huvvcnfo.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2jeahufhk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gt2ohxgwggq.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2yrziwfdw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnwsybfg.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gt2yaznlxrw.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gt2ksqviqvl.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2yruadfff.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gt2ynjuqedo.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2bahogzgc.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2qqnbcomn.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2xiicjmmv.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gt2juzuvlkh.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gt2qshbmqsf.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gt2ygqhxsoi.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2ahfxqoma.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sedmcjni.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2dwvlmwvc.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2mnmokbvi.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2uxqypriw.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gt2ncxaeuic.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gt2qybauzlc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gt2xntgbwee.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gt2xirooevg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2mrvrvmqr.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gt2dknxufja.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2pvrldgrd.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gt2bzbdchse.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2jvdtjgnl.html


<!-- 参考信息 -->