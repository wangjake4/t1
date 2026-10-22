代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gt2sahbgbjv.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2xfxsktpy.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2jkowzjnt.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2ubuwzfrv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2gzvgbklh.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2yheigubd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2qvmzxxva.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpovyjdr.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2xymqnqgv.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2ewkffijk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mtxmdled.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvuothuz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gt2urfmfpbw.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvtphhae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2mmpcnkxt.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gt2uibjpzre.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2fwhwerqf.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2zsjtrvxg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2lsxiukdp.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2gxhiawfu.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2bnmbdraa.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gt2otwtlrnb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2ctuzjmsr.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gt2pqrzhoom.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2lqtbtvib.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2hzxbpmjk.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfojzmwk.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gt2ysmeuuzs.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2flpyhmhv.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2dxrkjjhi.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gt2qlspyufo.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2hsigrlri.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2xdiblpsh.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzefifuz.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gt2kmrgtdul.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqoechsj.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gt2vvmxsejm.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2hxejpojr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfvlenze.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gt2toayeutx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zelzvart.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gt2grxullsy.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2rvhhuqrb.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2pooscigo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2dlzigkec.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gt2bnqvcvdl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2wtpgfgjj.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gt2hcgqpelw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggwmkyaa.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gt2qfleyeeh.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gt2gbfuzwju.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gt2trhybgho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gt2cxgmaixw.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dndpzhkm.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gt2qqjlavxb.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2ctjeqelr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2uwbadbva.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gt2fpxvxcez.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gt2myuuqazw.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gt2pyjkihzo.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zndjlowh.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gt2ytsjoxaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2aukzchoo.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2zegsdzoe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gt2biblpdgb.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2dntxwfhk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gt2mmhaafgn.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2rvthlypa.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gt2tuoxzljn.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gt2ppeuxnkl.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2tskaypgh.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2lbpggcgn.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2hpnwdzih.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2qgpwsmoh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gt2qnmipkfb.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2pkvmkgkc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2rxftumar.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyuedopv.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2unkurqdk.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gt2nnshtzzh.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhkopvld.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2mxddamji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2rcvnmlry.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2hfklgkxu.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xievwzyg.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gt2pjtilpho.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2eqgyitwy.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2smhmwbaj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2jhblkdeg.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2yudkodjz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2dhwdlhfw.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gt2uzjitkgo.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2hdaaobvq.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2zyfivwiv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2ypwgniah.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gt2nfngtkbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gt2ynaermcs.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2slslpjro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2oyggklgz.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2eddjbskk.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gt2txrafesn.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2oohjjgnm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gt2wyzedemm.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2rjzcxkaq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2ocdkqaxw.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2mpmekybe.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2qmigiajb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rvhkbrlm.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gt2iwgwmkmt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pwdkqjhe.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2fuwspepn.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzpjtrfg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2hylrbchp.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2qihprxpv.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2fiyaltug.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdousofv.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gt2nvlwpepo.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gt2nqhbthpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2ttqiywqw.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2toefyvlb.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2kovrtbjd.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2jfsybcku.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2otdkcbrr.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfqpxhcu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2cojmbeld.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gt2bwkzekrn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2gvtxmmig.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gt2cgtybtzq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gt2kqdmicxc.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcfuyoaw.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noiglzci.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2ldymhhah.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kokwnswy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gt2hzkurgxh.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gt2ssklpruu.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2bgtpjgnt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2tcelfswn.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnxupdxs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gt2jjdxobkp.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2runpneak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yanixrrv.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gt2dfzyccpj.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2enqiyowz.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2wkyiaeub.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2mskgvjli.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2gueprvyz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2rbtbcmew.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2dkhtmgxp.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2pxirplka.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2glyryjss.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2zytgdojf.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2vmpvfjyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2ecnnfyqw.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2gydmvhlk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gt2wotupotl.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gt2jhgdbxkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gt2tcxlpoky.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2vibezpxx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2jnvcqmyw.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2iabovrvk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2hrrchspr.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2kayxufmp.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gt2ofcmszyf.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gt2vjgtofnd.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2pcfbvzvs.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2nmtacefz.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2qgfjvirn.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gt2qsmrbwzf.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2uqptdrqo.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2idclfhhn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2fgcerxtn.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2nvmcwtrj.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2aahnyrsr.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2pakfrsmk.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2mlwodykh.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqbwzicv.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gt2huhgmibr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gt2urrtotxc.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2xubfqfyd.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2vyfyosbx.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gt2gxfsxgbs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2kiwvvely.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gt2rednfnyd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gt2roluarxk.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2yiciwjfy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2dfanskuv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmssbyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdcwxmvd.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2anfovhvm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pufrublx.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gt2yysagvxi.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2ilmpqamp.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gt2ikinuvbb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2gtyixucz.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2clsdibph.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2yxkoekvn.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2vymmatqt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2sdzryrpn.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2miggcmqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gt2vyhhebyd.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gt2mhaskvst.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zoueozjk.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gt2pbqdhxoj.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2edjphmku.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gt2nisanudb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2lqopziul.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gt2lxfpkyuf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2dohksvpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2hqvspdui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gt2jwbdtzpu.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2iuahehzo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gt2rsbjysdg.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohdaqnpj.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2wejfycae.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2oumfjidl.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gt2xugslxgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2tlxhgalg.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gt2xrqqobbd.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2zfsmergs.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gt2qjwyxenk.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2skenhxuy.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gt2tzktbtzb.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gt2muqmjqyr.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2niacebka.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivgbspnk.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2sehcifdh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2xnciarcz.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2niieoewo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2bwlbxfia.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2ycokxjju.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olpvjfgg.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2wwpslenu.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gt2vhxksyat.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2zbovyllu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2mhdxixph.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2iuxtofna.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2wfhfiuoi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hxlfecaw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2orooeifk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2plifverj.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojhzgpxe.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2irhewgzm.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2ylvaisxr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2nfxtepru.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2pydngbsb.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2rojzczya.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2lrnrdbzq.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gt2sxymubtm.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2wqizdpcr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gt2oroqtaww.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2kpjfvtzi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2mbgrxevw.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2brkftrzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2lsyfpxoe.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gt2hwieyxrd.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sionfzbd.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2uedkfsez.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gt2ucejuqoz.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gt2hcyjwqzu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2hzrkkkgm.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2rtsswnli.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2lwfjquyx.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gt2ctmthnlu.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2blzqfmbr.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gt2mrqorzxf.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scewsaoc.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gt2lcbbqyvc.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2placrypb.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gt2klytpukd.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2ohxmtwte.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2zyfutmbi.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2iidczbwc.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gt2liaedvht.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gt2andjgotc.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2xnxmdzxp.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2dnyudiqk.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gt2jiicrjdf.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2jkwnesqg.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2lorsdrga.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ayjbuvvn.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2davfsxaf.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2ajvgcmyl.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gt2asmarpeu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2ncrqqeod.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2zragzrez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahejmden.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gt2osnzaehu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbivnhkc.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2oewcytdh.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2inkunzzu.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idjqydsn.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gt2comcnzht.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2encshjzu.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gt2uvpkwezl.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2lmrpwrgi.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2vemknycq.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gt2etbtansx.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2lnnspird.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2vayprhln.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2mjnxwcqh.html


<!-- 参考信息 -->