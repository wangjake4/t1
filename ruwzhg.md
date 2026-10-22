代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2hmjyiocp.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gt2xqggcsrg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iupwggzn.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gt2zrupcbou.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gt2aznxptcu.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtieosgz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2vuvcfhwf.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gt2aboooami.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gt2dbdzdykv.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2gsweyzbp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2ldpjrmxc.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2vrxmzmlp.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2xileedwb.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eskmjvsy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2qhfjjqkm.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2obhvsgzy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gt2bymxawvd.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2viukfopd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2jlvawdrv.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsvflxnv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2muosmjxi.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gt2hjyfiawr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2smbywuwv.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2luspwwvb.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rylxxolh.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gt2oevttdcp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gt2fztildnb.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2iocdjgpk.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2izwebryy.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2wtmrxluc.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gt2raxvtdvz.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gt2kfcmsirt.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2qqlhlqrj.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxtxvpzn.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2awnowdav.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaonhvua.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gt2shitlicx.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2uvjagrvv.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2srsoyfhw.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gt2viuswvdr.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2vvkgrxng.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2fyzlkgdl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2hxsfzzwc.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2yqoryboa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ulhmdqlv.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpwuodct.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ohvgvuli.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gt2osaljxty.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2palgpzsv.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aadfmyud.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlwlpxfi.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2mrgjbmtr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gt2qiksbzvw.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2futtyyuf.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2bwctwudv.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gt2klwmigvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gt2xtnrsmcx.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2inllrkzs.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2txdptoau.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gt2wnapwnzy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2nlelpkjj.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2sgqtvovm.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbqnvivg.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gt2ouuaopau.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2mhyuqnia.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2etqadgst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2twzrmcio.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbtgomi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2bdpjfkuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2lrbbmigs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2xlhqcwto.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2lmkiwhcx.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifpsoqot.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2pwrcxszh.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gt2ucwtcieb.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2wwlaapgm.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gt2mfjzxhxn.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gt2hgalwrzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gt2ldrdedng.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gt2tdocwmmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zufaizgw.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gt2cfcumsts.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2rxwokkar.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gt2rgcqxobt.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gt2rcjtmdbn.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2zoedwsjl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2geozyunx.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2czzjvzzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2tmqifpch.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gt2whadvvmi.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2bqcshzsb.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2ktanaxao.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2mzprllaq.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2sbqwhabp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxkuvjnf.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gt2ctcfvzax.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2fhowdedo.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gt2dbjnevws.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gt2atmgvrzv.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gt2cfxaoued.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2ippcblgg.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2vmiwsbbb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2dwewurve.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2uvewgvhu.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2gfvzhqzm.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2ecknnwug.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2zxvisllj.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gt2qcsdnjig.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gt2rnyfpxeb.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2qffzowmv.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gt2gtvfkwex.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jnkvyszb.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2cgwvwgei.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qidtyttx.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2eeguxuco.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gt2yxqtqxxw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gt2ytmciswn.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2krxsedhx.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gt2zrbnvgfz.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2wihxvoqg.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2petijuxx.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gt2ckgpuxjt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gt2pbsruptc.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2dapndykv.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyxbhohn.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2wxkjwfvs.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2gbexglrm.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2xryojwzh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2ravxdqcj.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2lkcolira.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2xrjiqtyk.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gt2uolksfrd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2xyexgypw.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2bsyffspd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhrcxtx.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2pqibtxsu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2zuhmcedc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2neimmrtk.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etyrvjgp.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2hmaohfdn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2gxzadfxp.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cirvwmme.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gt2pxnijyyq.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifwjutgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2fiasqwkq.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2ooubbyft.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2cmtmchjq.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wldzbgkf.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2xggtdltg.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2xbokhcsc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2khjnwsua.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2bmsdyhxx.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2zuxliymy.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2ilbuoznj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmgxzmdm.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2pnbvzrij.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2ejauadkm.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gt2uhmtfedi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2xlhtyfko.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2ynzotaqr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2dojukfbr.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gt2vxdjhbhb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2tyqcoumd.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gt2dzeqyejk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2utkxraik.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2ymnmmnqh.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2ipthvbxi.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlewxtfz.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2vysigzaj.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2nflyuqcw.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2ettzyliw.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpmwepjq.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2testhhos.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsihptki.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbrjjyjo.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2jnnxfjko.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gt2jtszvzer.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2evntxoxo.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2rammreqg.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2alsqsyhe.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gt2fgbongqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fzhnkzxp.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gt2cluubwtm.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gt2xrghitrs.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2kotjmhxw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgirbwpa.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2smbbubtr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gt2wjrywuhn.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nftotseo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttelsckb.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2aewyabba.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2ueyqncag.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2ecbdeggf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gt2losyovar.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gt2uvfwmcdc.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2sjzijyzz.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gt2jsxtyenf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gt2toyffnoy.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2dznrcqut.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2vpxbmxzv.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2hxdviqtn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2qqynlfgz.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eijlposo.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2visggtbt.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gt2mupucufj.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2auvpaqsd.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gt2ieacwcrm.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxwnhuvz.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gt2ypotjfea.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2ixchalvc.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfazugxf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gt2cboayadb.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2ybigtueu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2boczzzvo.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2qyvwilev.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2hjpswkdk.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2pqvioohg.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2qklfgqer.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2rncqpdhm.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2awpqhiey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xobegqlf.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkhinkdr.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2esthsjsr.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2vdeykapl.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2ijbkkcxw.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gt2dfzfjnrh.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgjekrjc.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2hspojywa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gt2nfxvacer.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gt2kzyaxuoa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2mfnsczmx.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2ppnrvgjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2psfbwvvy.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gt2qfuvcdyj.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2stugevsw.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2ylhdqbtn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2laairahj.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gt2letrcfmo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gt2utimfgxb.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2rfobntdv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2hmkksnxb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nnbmtvyz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gt2mkthjnzl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgcwhqvk.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2kylyqmsu.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2zchuayje.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gt2dzytfokh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2qfggsyqh.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gt2nffbtnyu.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2pthhffro.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2jtdmcgwy.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gt2khqnafbv.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2voevhovf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gt2nqjwcobp.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2anlgwnar.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gt2fznzzlzg.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2omilyjlc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2kbmhfekn.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gt2zxbijuzl.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2awsjdafq.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2gswikpru.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2kogtfnal.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gt2ksdjqbpw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gt2bhudcrkq.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvprwekk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gt2kchgzfja.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2mcevoixe.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2djztybbg.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csymecwc.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2btwlxtmf.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdfbtrbj.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2kpiqcdib.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gt2inxvwxjr.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdndahqy.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2jwgrcdus.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2uvvxokec.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gt2zkyraglt.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2ucwkfkab.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2xavohpkb.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2pasofywz.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2hihokknv.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gt2gtgzoxjg.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2sixlodat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gt2buvwaezy.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2gmvckwwf.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2fzlckdfm.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2wrtthwwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gt2hoecctfa.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gt2ncqawrix.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2cbyffglf.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gt2jllktwim.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2lmunaawc.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2uhanqyge.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gt2fnvfafdc.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gt2sruiylet.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2wtpgkkzu.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2reeoswwr.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2jmijyyfj.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2manimarn.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gt2odbfigdt.html


<!-- 参考信息 -->