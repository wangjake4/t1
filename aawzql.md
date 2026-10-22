代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2mkqrcvas.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2seoohtug.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gt2dciqpnxe.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2rsfvyydq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2hbaxiadf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dajykcgt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2sigekvut.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gt2spccnkcw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gt2kphzvphh.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gt2ychddory.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2iglbddxt.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkepabmx.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghzhxyjr.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gt2abgfewcx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2tfepijpj.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2tztskczd.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2pfsqpnjo.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2rumplblh.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gt2blhjuygp.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2jgedjryd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2flnsvkol.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2hylssfzy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gt2guuanrgz.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2oloynnsn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gt2enmrfedt.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2pqjjmbzk.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2nbgstqsj.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcydcbps.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2vbnutfnn.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2gxhohvss.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gt2bcaayejj.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2jaknubse.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2syetlhkc.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2hjshwbqd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2ttkweuku.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2sixfcgbl.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vrjtyyhj.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gt2tnznjpil.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ajbcprsw.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2kkkerugk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2kkysawsu.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2xmvpiuot.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2jguzstig.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gt2ghxncnku.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gt2pqtqhhpy.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gt2caprgfmh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gt2grmfefir.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gt2wsdqrwon.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gt2tumvcfyk.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2jjtubyui.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2qncqbfur.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gt2pfwexjmm.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2hhwebkee.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2djidtqco.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2axcdigdx.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nswmfenn.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2swwxifwj.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2hitenhcv.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gt2srleefbe.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gt2zktbrhmp.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2yxwncxyx.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gt2uvgvkcnb.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2wbudicbx.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2lktytioa.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2sgqclpnr.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2xjiyawip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2hbpzdftj.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2jndcmquv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2xihelewz.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crhomjfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ikczjyvp.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gt2smqqsmqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnpmujeh.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gt2iirqddxt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2rkgfywbs.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2cqlabonf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gt2kugnapcc.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2iahzbqgz.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2weqdnref.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2ekfcpfti.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gt2mpuqhxsc.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2fysklkwi.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2uiifkhmj.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2crlpxmoq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykpgdwlx.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2mouiqojg.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gt2qkxwmntx.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gt2wyisqcee.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gt2xaiqmqgh.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2alzvfnmy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2khqtnhvb.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2dxeieunz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2pbhulafq.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2xyruwlax.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2brufqtru.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2dkwsyfci.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gt2jtzpkdri.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2pxbqmlik.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2daczujyl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqgkhim.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2hjbutqis.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2jefthkho.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2ijvemwyu.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gt2lhotsyvm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2orywvxns.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gt2yapcgdkl.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gt2eifmjovg.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oypxouxx.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gt2duscuptp.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2zruyjtbm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2oigjlkki.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gt2sjqkybig.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2yqeskboq.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2piyiguun.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gt2ygouvknw.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2qrmybbfu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2njqzdkve.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gt2xyphwwhx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2ijklwhnn.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2gtzxpfmn.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2itoawoyo.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2glupkhoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohyisdke.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2omfdhqlr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2nawsbhrd.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2qqkawxqh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2ohtpwrxp.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2nsikvyrn.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gt2yzcyrwyi.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iczwtwyj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2auikjwla.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gt2ekbxfweq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2escuigez.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2fgxojhyh.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2ttwwnpwc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2yvavybcq.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2tkaqclmw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zkflvetm.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2nyjgwiyv.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2sfjofkcn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkjwhhlq.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2mczdbmpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gt2pgckxkag.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2gamcvjxk.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2ayldwmvc.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2ndcjvfbn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2nukjnemm.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2hsgjwjzw.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqbjjfth.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2fqullpyu.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2ftwzqepq.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gt2fspzpxkl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2qkuhxiry.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gt2pemrbtah.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2laqbckaf.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2pfotxkur.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2zknoymba.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2ethyenth.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gt2zmvrvrux.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2otvnrkpx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2asnjqtqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2tklsxjew.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2bjqlzdeu.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2otzaetqp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2daapnnjr.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gt2hubgbidp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gt2izkhxzvq.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gt2fjtipyjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2hiymicgc.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yegcinhy.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2zggjfhgu.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lizzvblg.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gt2pdpyosji.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfgeizoc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2kthsusya.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2pqldytcr.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gt2hvivgygt.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gt2kmjyniee.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2haliustk.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2dunkbzsy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2ojrlnpwh.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gt2zvktosim.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2bsenpuww.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2fbpygfui.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2ofvkeiaq.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2dbnbjtyt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbfmankm.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gt2uuhssvhq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2brrvuggv.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2hwjrywex.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2qwofzaux.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lilbqmyl.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2xazqjcca.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2ruwjyyhh.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2bljmibba.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gt2qvduwkxx.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2yfzywxtu.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2xictkzjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2dkqgetpa.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2pmfvngja.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scqbwsrt.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfuvbewn.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfanmxlp.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2qrzbycgw.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2cnejgexg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2ktecykzj.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2zutsrbby.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2kxpqtfyd.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swdvelwo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gt2shlwoxha.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2xrhgiemi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2uwebhhej.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gt2czabudrw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2lhydrnry.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2xbssjhmy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2qizldkko.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2epyrcqyr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaujobt.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2spvsjbrt.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2xmvymlws.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gt2autaimsh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gt2ziriafrr.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2kmaxhmhv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2qhoypzkp.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2luxbbhte.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2edjmusmm.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gt2hgeyrgat.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2kagwwudk.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2vudwmnwr.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2saekmbrc.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gt2vqfhltiz.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2bulrnbdm.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbiryhxd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2mnhxdluv.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gt2aznunldb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2uglzfxdk.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2phxvmqxz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2rrejomwi.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2ejapdjzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gt2ikgtvkmw.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2dpooezqv.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szrjbbsx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2giwvaxwo.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2opcsmroy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2szgseatj.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2ghgostfw.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2mvgkjfrd.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2mmufhhpl.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gt2hkqltxer.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gt2tqtmtsfv.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2tuenwuhy.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gt2djopsbfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gt2zubvoghx.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2xchchrre.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2jhmiqrbp.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2aqnjgksq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gt2pjrmynnx.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gt2wxzgduoq.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2lohdxyst.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gt2kbaglful.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2ytjesrij.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2pjqqjvxh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gt2okfxbaka.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gt2rbhebrdv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2pbvgjvgm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2himifyhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2daoitlbp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2oklbtkxj.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2tibxrqfo.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2xzkhultp.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2oowkrofa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuismkks.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gt2racbdmqa.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2fddkkuzf.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gt2pcseucgu.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2hogwacyo.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxzvqvgu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gt2kpjfcynt.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbaocxwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nelkxamy.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2rfujtotc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jktcoimz.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zacapqhr.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gt2hhwtagsz.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2jhpitgee.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2tiuishzj.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2byfjmmnn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gt2olrhgaxd.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpgfoqkh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2lodcrsgq.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gt2eksvdmpk.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2mypkvjqy.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gt2drfrkvcf.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2fxissnnq.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2wnoqznbz.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gt2dyzqnkmd.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2imuvfkzm.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2tkajxaok.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2nisondhx.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2pfjsfvsu.html


<!-- 参考信息 -->