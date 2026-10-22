代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2xifreoaa.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gt2uanfvods.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2rcznpamm.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2mjsieqxl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2lptwooja.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2zdebwaor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2qdrvzzjh.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yibgakrw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2wwfdoyfw.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gt2fvubecee.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2cihdidre.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2sdrhtjav.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxaboxrb.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2dxbpppdg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2xkibagkq.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2klpvzufv.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2cxsoykzq.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2jrafoxin.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2riwoahya.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2sixjjucy.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2inxzvprn.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2ygqxcyer.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2emzgpage.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2bejakzzh.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2jhmhqbcp.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2ubvjvrdg.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2lfhdkndi.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gt2acmynhui.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gt2ovfpvlyg.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2qyyaxsxp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2foldoyoo.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmsfpfky.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2ccxajvqu.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2slecrsja.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnobodkx.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2nslmbmfr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2equxgezm.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2qjtuoyxo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2leevsxsf.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2ieafltdd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2xmejggjo.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2pautoezu.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2jlcbplin.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbgasmrl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gt2niyfyxwt.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2bkjglvdi.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2amhhqckn.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2kbyxcgye.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2tzhjrzws.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2vakrtadt.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2ebwrceyl.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2pjlbwtgb.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gt2uyzzwuvp.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gt2rqtqscyi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtsacwfc.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2vzemilsv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2iyyjqorn.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2rhgzzmrf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2zjyklipa.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2enmufaeo.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2mophatpq.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2althkmcd.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gt2xfsimbeb.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2ditraxov.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2dvmlqada.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2keebpero.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2balcivbe.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gt2ypzbykll.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2ytgzzbyb.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2bncecfxx.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2tetruwro.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2qshbbupy.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2szmixtbs.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gt2thbqhdvh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2gtbkswve.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2ogpnzlxi.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2wpwspvfq.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gt2cxbjsssk.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gt2znmuvolc.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtnyfgop.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2vcbiffin.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbsppyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2hxfyqcht.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gt2kylplnry.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2ttspxiyr.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2ajpotnqg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2udxgfcmj.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gt2ozqdwftk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gt2hqcmhawq.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2iamdylbw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fftptzff.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2obzajvss.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gt2kqjjfduc.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2zrjrnhin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2erkpqddo.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2hnfflrki.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2oqtrsmyi.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gt2vnyflgio.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gt2nnrnxzjg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2eobkglbn.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2tvywqqyg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2afsozngj.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2sjtwucrv.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2zewqfrlg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2ijlvggoy.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocucezol.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdvecfhc.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2fqvbtbzr.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gt2oljorbmk.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gt2yrtmvgfs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2pyrskaoi.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2hwvcqnpo.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2xainthdy.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2zuehljgb.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2numyljmf.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2zgusnyxl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkeshqoz.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2usvrnjhb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gt2jsbpjywj.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2jstddfcv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2iptolsvu.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gt2zedccrhi.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2leqxsvdb.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2dnjomfkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gt2gwmwttna.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2xsgsbzcr.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2pzcozzmw.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2rcbzqaww.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2aktrwwho.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gt2ftggoqks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2oholrlfr.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2fxmnkgvl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2gygkgmie.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2nxdiqvzx.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gt2uwasaclj.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlkbkjja.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2fhbrklko.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2dtvqbeyc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2mrzqnrzz.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2yqrfpzli.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2dhtdpvvp.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2ikckecya.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2skwlsfyv.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2tooqporw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wycnbmix.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2psowcvng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2ecfrfpxz.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2gkirtbmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2qilfdycn.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2jefuhptn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzapjaca.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2sygfkpju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gt2vlcvjetb.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2djjbyuzb.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2umwxpooj.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndxcnyfy.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2ffjiqxia.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2knkvsdrg.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2dqexyjke.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gt2yrxtkkyg.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2ahaokdvu.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gt2xbaedrcq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gt2qstmzvwb.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydnuoykq.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gt2kooohvqa.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2zdqbgxer.html

#endif
来源：http://dali.tian-w.cn/Article/details/gt2zggstpum.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymdkvggw.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2rttgalhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2ahtjnymh.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gt2cmmhlcrr.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gt2jgrrzfsr.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2cgjeigif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2vndtkmtn.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gt2vbhpnplm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtieojf.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gt2hpktwmis.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2weifclkx.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2tznnpkcz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2bjcaqsvw.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2wndatowo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gt2nitrfjvt.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2odhmooni.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2rqjpdvbs.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gt2adyklvcg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gt2jctpiuau.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klnglpda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2genyrfew.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2gydfnwlu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2frnqndtm.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2klfdjidd.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2qooklczk.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2ehzqjxud.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2erwrafwm.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2vhlkwfcu.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2tgzvdnir.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gt2kajsoubz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2hdaiatfs.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2cyecwbaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gt2wtldcnee.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2qxoljexq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bweujlnv.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbmkoejk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2tbtuuyyf.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2xskwdjhc.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2phybiwsc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2xqdighln.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2ybvztgkf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2vmqynbda.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2jfilpaii.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2hpybmvve.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2pwultixu.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2qdwxxpns.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2inaqsadp.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2wioczxqz.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2mjbbulwh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gt2piwlcmsq.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gt2oqsxzoih.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2gpsaujju.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gt2kngypzku.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2dforfyps.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gt2srgkktva.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2syttlszn.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaidegji.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2bkabeyse.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2rlqwpwuo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2gbtqockc.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2xnpskgum.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2bvldterm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2otuppvnq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2gghifdfs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2creablzr.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2zplbardd.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovwyqarm.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gt2gvlxoneb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2tfodrhaj.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efxnoels.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2zxivorot.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2pmosbtie.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2aobglotl.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2aijtwruk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouhfhcuw.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2iwijuhup.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2iacsjozk.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2wdgeyugb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2krejbvax.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2zzepyihn.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2jwmjdzpi.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2jyofdfwq.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gt2xtdjeexw.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2ozkecfyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2hczlntrr.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gt2rqayyiuq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2gizdyldm.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndxwtjjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2zzbflbzc.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gt2ayuccwnw.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2zwswowzq.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gt2pauhdiav.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2dbvobtxy.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2qkpdgegg.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2pcurgner.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbbdqiad.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2ilwiprfc.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swlpgube.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2rmfbprxh.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2rffvrseu.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gt2fuluuugt.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gt2sjbnvqcm.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2nlldzxzu.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2nauvqehy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2dnwruaoj.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2whnridvd.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gt2jhcfqyeo.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2peyzkdlk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gt2bfbqbjsd.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2elospons.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsmnkihw.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2vebfxqmt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2ctmgrtpp.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gt2opzxcfbn.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gt2wjwynzun.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gt2iqubierx.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2sjdircat.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuqebcgi.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2ucoytqwh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaanmdr.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gt2mqexdjkh.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gt2eblyfhrx.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2vrgiwggc.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uthhrduj.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmuqxcbd.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2yiphjxyd.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2ahjjwveg.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2aiaybztn.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gt2gcehvexg.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2vqlbtpwy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2wpgruaij.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gt2nrhjrvcg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2pnazmzvb.html


<!-- 参考信息 -->