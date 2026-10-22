代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gt2rpuvapkm.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2kpndreze.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2tyuagcqc.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gt2kovlnlpp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gt2iboohrws.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgzjklxe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2qvfslngr.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gt2lttjtjur.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gt2ypuccqsa.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sroynbud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2tnyshyra.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2azhzjcmq.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2jnyngcwt.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcohqqks.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gt2sewhlmiw.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gt2yeeknyze.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2geubgnil.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gt2kyzzxkzy.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2ccytostf.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2euooeamd.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2mhgowdlg.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2hdrcaqqp.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2bzdowsbe.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gt2hiqskzxc.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gt2dsbbvxyy.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2sgoovfkc.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezuvygfg.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2bytyktoj.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2tgcikggp.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2wdsdcqqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwfwpams.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2gmoqjujz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2xfjrkmfd.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddhwczwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2pcuhnlxz.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gt2fdpejjag.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gt2qtlrnddn.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2khhvndkq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2wsllcuvw.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gt2bgwteccd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2hlupfuei.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gt2tkinwaeb.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxpqtybo.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2vlrnynpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2plcdumjc.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2osztpkye.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2uvcutniv.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2jrkgjued.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgoxvqjz.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2mxqjukzj.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2dmfryolq.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2kvljmzae.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2lokczwbq.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2jdjmplpq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2rqzrsjnz.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjftpdmq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2nltqhhuy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2gdsixprh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gt2bmyrafhz.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxvhtxqv.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2ihfxtypx.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2wmtdbccp.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2jyltrzmc.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2povcanoy.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2vibiutmu.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2wbdebegl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gt2gugekqhb.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gt2arhilfzy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2zfnhoyxb.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2gwaoxcnm.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwweldoc.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2pajdlmlj.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2gjwlyjnl.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gt2bfmcwarn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gt2ezibtzlf.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2jdxueair.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpqyzvky.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gt2eseqibyx.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2awzkauzy.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhrtkryn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2hyyjiujz.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gt2czdptjni.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2ubochhlo.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gt2bdizsqfw.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gt2eqhiiahf.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2nhrhacqa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2zyocmikk.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gt2vetacsjt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gt2gkpyhjoy.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2jowpvevp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2fndcakvn.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2glhzvzpq.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gt2jweforbb.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2iyygnuax.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2wfygbooh.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gt2kpaalryj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2yjcmwddy.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2ohwkvgki.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gt2zijwhecv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2irscxauw.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbgjghfh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2urmlitqc.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2gejkrcze.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gt2hhmhxurl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eywjnnwr.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2fmbytzuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2uufbskiu.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2zpedzigo.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2objmuagj.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2ndprsknk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gt2iqjsupda.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2ssunhrgq.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbfhtmoi.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2vhtszpca.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gt2rlifwpbo.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2uhkdicvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2wyqodung.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gt2rtahxkgq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gt2iskztznl.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2cauvxirt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwmgsptf.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmulleeu.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2nejjrjca.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2anwoburm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2byeuiebm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2kayjvkpu.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2phxakyop.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fepgbfmz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2stwxuyhe.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2ixopsuou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2sojbapep.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2bmspsdvg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2pzwkolfb.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqgfwxhm.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2ioszpgfg.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2ftxmuayg.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gt2qggugqno.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2lckdnmai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2xhyluqhv.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjsvfbkh.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gt2nsfwglpf.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2szvfihjl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2yoztxzkj.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gt2xvwxqmjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcbuxiwe.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gt2sindbqdq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2yhazflzw.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2jepwmkrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2stnyckgn.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2oswtoldg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2pvymairu.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2ushfqein.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2itxvlmeh.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2fjsgvbqr.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2ezvhtgdo.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2zybpqhwb.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2oeqtygld.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gt2jvcrljsy.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2zhwnnmyq.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2ynskkwfp.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2qpyjiesn.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gt2ahevuczz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2vwnxxjjj.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2ftywcgpt.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2tjfdjxcf.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2lbomuwyr.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmycljwm.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2bbrvixad.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gt2gzdjohym.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2cizhnzwp.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2anfslegm.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gt2kjynfyjd.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkqnijla.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gt2vfwdssgm.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2vhfxtmgn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gt2auvgdfzq.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktfnydoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2wgskkpyt.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gt2vbyfvdbs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2wnrirmsp.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2qevzzqnf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2qvzhfdgj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpuckvi.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2ijwvxaof.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2mwebaiuc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2mtontdtd.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gt2hxgvcltg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gt2owctvpdx.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2nsrfrlow.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2xcrzfjfz.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gt2uulcpmjm.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2dygvveko.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gt2dpbfcmla.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gt2tgjpwjhp.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gt2mbqgchoj.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qldxwucm.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdneghzd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gt2enanohnu.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2uejaqxhp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2kbzfqaqo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2mfokrbja.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gt2gxyiolag.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2duyfqhcv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gt2drxynzsh.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2rjszvemn.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ygsajhfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2zheierkh.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gt2ftqkvwre.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2ygosyadg.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2milbhzbl.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhdxphha.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2pvepemjk.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ourczsfk.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2kziudukf.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2genelyao.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gt2qzqyulpa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2kjhmoygz.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gt2dytgipcl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gt2galzsmad.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gt2bhgfalji.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2tpozdyya.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2hgbooeym.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjsvjjev.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2imoqsxoe.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gt2ahuqjnjo.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxdgxerx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gt2lpzzixwn.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2fuljrxoa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2kfzkegzj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ltycrpox.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2qvcfgqrh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2azshskzh.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2bdfszrbb.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2jpaqcjus.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gt2mphjrjie.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2nyovuxwi.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2yjvqyvbh.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2ejtdpbpy.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2cuqvsdxu.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuadkdro.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2qkjbryxt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2dpgneeew.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2syguqcaq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2aywchqbu.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2rmedjbam.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzqtukvy.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2fykalrnb.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2qubpjpuf.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2spkwjehg.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2fjcxzfcv.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlomokvg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2ablvjaxz.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2auddxmyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gt2veemyevm.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gt2olhiuodb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2kcdmmmyo.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gt2awuxqxco.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2qvemoaej.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gt2drxenfjs.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2rjovxeqf.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2xfcidnqp.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gt2evyptudx.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2icawfarl.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2uozkgwsz.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gt2ipplxpgy.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2blbtmjpy.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2ecfzcgxw.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehmdttek.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gt2xnxxbaut.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2mmwiihmo.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgfoggfn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yunelyac.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gt2bjlwelew.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gt2kzeuzpjo.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gt2eaeqqegs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gt2guabdhky.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gt2wipqzdqo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2tmssijks.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2phpnwmkv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2eibctexm.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gt2lmavbydo.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gt2tswvegwk.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2nvwfkmrg.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gt2fsjlxjzm.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2czicgxyy.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gt2orktkzzc.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvjjbpux.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2oclgsarq.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gt2igtsciez.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2qxuxoupu.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gt2vizboxwt.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkeauioz.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2kwgvgzco.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2vgdfisko.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2maifshdl.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2wnidultm.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gt2dkmzysmq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2tzaefisz.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gt2zxecinoc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gt2xfabknko.html


<!-- 参考信息 -->