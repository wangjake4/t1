代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gt2mfmqfpne.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2ccgckvuw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2ikfhonzt.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2ksqlwguo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2krfffcrw.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2nzcbrzeo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2ilsowjap.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2wchdcjnc.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gt2rwadmgbs.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gt2vmilktoj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2vffgping.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2cymdlyfx.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2dfmeogok.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2ytradeqk.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2aqathely.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2hpqbvvmf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2fmdorbbs.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2cufilshp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2qsycfhyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2fyphnlgx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggodzanb.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2csphrzda.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2dkraiftx.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2eurpsrlo.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gt2xtszosfq.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gt2ovjjxrxs.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2kpvboeyf.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2feudhmaw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gt2uusetngc.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gt2isabdipr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gt2zqtipdns.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2aqkuzdwd.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2nzzovjhf.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gt2lstyittf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ulvxlrix.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgemaqcc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2luyshhro.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2kzegseka.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2kvufoyjy.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2nmxbcwrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2tstnccvj.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2miiyjdaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2ykssmfdb.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqqopftc.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2giaubvhw.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2gfdmtrit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gt2wpdpyfpp.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gt2qwhrmchu.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvgdnnij.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdpfobss.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2fyquobcz.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2fghzjars.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2rnmamemu.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2ruxlvtvr.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2lzdtfkjv.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2cpivwmpq.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2bieiugho.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2mdpvoyvc.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gt2xnqdazom.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2wcqykblz.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2tsdtqlpv.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2mgkcnnyz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2lifgvdgg.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2vbtufjyj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2nnrpgdwy.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2yztuflwj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2xrsalxja.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2qvpeghwy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2yjhelnba.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2hklzgxwl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2qxhdzjni.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2biymybvy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gt2rifizqgz.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gt2cccmeucw.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2gmxsjheq.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gt2flwhcejz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2mdtyugmg.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2vvpzgapj.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gt2tbfusgte.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkqhipus.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2pvplcabu.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2fysxtfrx.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2fxhbjbwp.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gt2drduomsd.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gt2kmdzwrpj.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2heckzjuy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2sapkqgok.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2vmsbpciz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2eelpgtls.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2uqvfjent.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gt2etuxrncq.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gt2xfsmsbfe.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2netitlsy.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxbxjgjm.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gt2lqmijvjw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2czqvyrfi.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2mlqbxtwx.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gt2plerdqrv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2qqwvikae.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrvxuqib.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gt2dyqsnlwa.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2vkkpkwtq.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gt2gaolafmz.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gt2nwulcxnh.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gt2kimaszji.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2ttymdooe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2qazgozge.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifdryocu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gt2mckmheoq.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2ccxyzzof.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gt2gggqusge.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2phhsesay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldqpihyd.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwvrebao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2gixgcjaz.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybshbnwv.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2mfcvekgv.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2bibmbmhq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvymjfsd.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxppccea.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2axghednk.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2zkknwdrm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2xochyxub.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmyddmci.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gt2pqprcvwt.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2mijtndeg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gt2dvkgbfgb.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2rzohljxp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2bzlkwofq.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2utxnydsv.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gt2gkpphrcr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htzattjc.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2qnxlsqbc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jpwycbzo.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2ehmpbmhy.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2dgqgjtrq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gt2pislmqpz.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2auovmorn.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gt2yccazbww.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2vimojoeb.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gt2qikzblyj.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2ltlqwkcb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2oeepaicv.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2pubagzpp.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2xqwdzkuh.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvqqamaa.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2soitnrtl.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiacviay.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2jmqhfzfy.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gt2ehkfnrud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2gbvqvugk.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2bexmgjhk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2scydmgdv.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2rdfmvuct.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gt2jktgmlmj.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsyygrho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2oprcvtde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2jcmkkyfm.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2sbjpzblf.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2ezogmhvn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2oxgtdxer.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2rgrclouc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2xikvdgjj.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2obtxeeaw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmxdpztt.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2uvfivpcj.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2dedhbcpd.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2ceaeblyl.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2btfofkle.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2cnrykepe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2nfzqhxtb.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2hbwdsgyf.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2yudvupbm.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2vfvgwbar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2xwmocjas.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciozdkmn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2kvstzwdt.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gt2iyvziapu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2zsosmkmh.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2numtpowh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2vpwjukgx.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2iuvvahmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gt2etmoxqma.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2qhrevnyw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2krieuejx.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2chxwtaqv.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2tpgjlwgd.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2xsxpyuqr.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2ccetrhny.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2nfndexer.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2bbnxobac.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2jweebqcu.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gt2etfmtlcq.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gt2nwlkbkxs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2ogvfysyu.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdpqxaxy.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2crfpvhbn.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2tmlbiqys.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2ywzoynil.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2hxfrsmdl.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2udlwfuax.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjdmkgis.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2lhaynljj.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2grolfviw.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gt2tquzaogn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2jzftpqkn.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gt2edkllmdu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gt2ynnubxnu.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2udllqqyj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2grnnnujf.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2krzukopi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2urivghkm.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyfazish.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gt2zcwqffuz.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gt2gginkyld.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2htpwichv.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2nqpdvcef.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2uddotfeu.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2vrdmukkm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2aushpdqf.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2vfiqrsxh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2hofbzeyd.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gt2xsyviujl.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2hnoqrdna.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gt2pqveqkmk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2huwonohu.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2bxkjfdpg.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdngmrpq.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gt2rreltdjy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhtbydhx.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gt2dmkuctnp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2prdcgrzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2ccwsebna.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqxeueui.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2pweyodnk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2oyfgttxb.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2gdkvourw.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2pqginypd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2eithmhyz.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puwpwhpn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2itoqbqhu.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2pnobvfrg.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2ddpoadvg.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2eiblvull.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2zqchnbbn.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2rbmpxyqv.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktfthfkb.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuqebrjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzatxbgy.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2qgsefrzm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2crkmnuli.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2owjtzaxj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2wvwrgcny.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2clcwfxux.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2vrawfmpd.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2ynupdrvt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gt2hdszocdp.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2bajeqejq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2pwrgoqus.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gt2dwelpmsi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2zgqrxrnf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cdhrjafv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqlgixg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pdspbtwb.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2scpnqgzv.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2ulzijres.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2yzylwtjq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gt2sapjliwp.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gt2chxvykgi.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2nyahqjhw.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcbegadj.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gt2pxgvdsvw.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2wmalyiag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2kjbkkvpw.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2hupdkuas.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2fassulpj.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2nsybzfil.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2mihkgbub.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gt2ediobrxy.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gt2pshnyfkb.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2dhcbtdmc.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2rfapltps.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzjkghrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2seaxgwqk.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gt2dmglhrwj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2gpwcvpcs.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxzpwhyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2nlkopuhp.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2oksahabg.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2qekpcyfc.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2pjhwdker.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2jgsxqtap.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2dcanldhi.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2gbdlqziy.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbfspmku.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2sgjjslad.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjvinyyw.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2hggdgtom.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2zehxiwmf.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2quruhagd.html


<!-- 参考信息 -->