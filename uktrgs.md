代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2lnmrrbpj.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2ozjakawg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2htphycyz.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gt2xsbvnapi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2jkqwrazs.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2zcmmorne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2kbrfhokq.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2grsgmrca.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ysjgrxio.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2ddqjdpxl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaivajau.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2xcopzcen.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2eejsdzvz.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otusgkmq.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2yvuvdzsy.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2zbnzzvoq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gt2wxkwcxlb.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2pskslqbg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2pdokegwi.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2hmlkxdhe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gt2yqikoclk.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2loguffln.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2fttbilru.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gt2yzciluwl.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdnluynx.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2ihjdbuak.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2vdccmvrq.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2fqucuwnk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2otlcupyi.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2xbovifkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gt2oawrxlzl.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2jstiahux.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gt2tpykiskt.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gt2iodwfnpb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkuuqgbi.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2gvvyfkwu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2vpimgtdq.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2poauikqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2jdvjllmz.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpdudkfv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2doeaskyq.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2fenlxsrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2scnjsqmi.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2hujpcolo.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2zszfafhq.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gt2prdvocaj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2xdgkhzkq.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2diobpzbr.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2rxiutbhz.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2rvlmzkpb.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gt2ctjcumzm.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gt2ksfmthnk.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2lwpdtnjl.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gt2ealevioi.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gt2wkidnxnv.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2hsjgzdgp.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejaxipiz.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2qxylvlbt.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gt2hbqtttkl.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gt2vsnahsnh.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2leiphrys.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2cgpkjqdi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvrmvpue.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2awuevunh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2zsxmanft.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2zvgyezif.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2fnpeqkth.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2hyhhqtbo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2udpdgmuc.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gt2pcdvrkbd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2iplxowzq.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2ipwwvino.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gt2uhsvttlm.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crpkfrww.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2zetoryot.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gt2pwqshvlv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iguzopkx.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gt2fiuqtrwd.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2asbvpjtj.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2pambcivn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2lxnkzveg.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2ovapkisn.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2cbaaeqve.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxjbpqra.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gt2adwjbjlr.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gt2hqfpadqq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2slbtffxm.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2mdhzipxa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2ntncvqse.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umrssohg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gt2gewjrteu.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2xsnjjpqf.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gt2kfsdfpqd.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2sxvpgmkj.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2fhqcmpxc.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2olieiflo.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2pfmgemqg.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2sczyghcg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gt2dtchgyyc.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2ubdnwcay.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gt2xgozxviq.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2qrifdbrf.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2jjergpym.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gt2itqmwdim.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gt2nsepcyzp.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2qmbbfrvu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayoebivp.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gt2talbrfmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecoawhjs.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2ouxpbcbt.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2axjninnj.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2lghfcjrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2wjigmjvd.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gt2gwtjmnhy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2ewekvlfp.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2xcttepke.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2yilgbbti.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gt2dgfbqpek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2zmtabgpq.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2swpuljbw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2jpvddmim.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2riiejlob.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2vqgbxrrz.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pagzdbqq.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gt2huoxyvms.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdsrfqrq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2chnzumpq.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmwtmonx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gt2phixsegv.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2qtddbxjh.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2nuxteieo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vphmlopc.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gt2inashhko.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2sgsckdzn.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovbjosww.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gt2yvrxnuth.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mgpyehrd.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2jmsuygfr.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2wtqsnfdo.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwbraohp.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gt2qpjepkrq.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2rpgqfgdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2kyzexdhn.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2cxwhxggk.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2efkrpplq.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2lqjmbpru.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2llixwvaa.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2nayrsdbj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2wquxjxff.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gt2kcqmowsw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gt2eztprsdk.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gt2hkwkfona.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2nmbwolzu.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gt2sfwrfqoy.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoqvxyio.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2etpwpgch.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gt2ithvpljg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2tbqykakv.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2vyrpxeiw.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2lwtgqlct.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2jpfbuhlc.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2rkhofrlk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2ceimffor.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2yhwwvxxz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2nkvsoqou.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2djcaqrgv.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gt2woxfipma.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gt2qynvnfjj.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2xfbxuzjx.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2mebwfrhk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2amlmlrmm.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uynmlfvo.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2heahboly.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2raaqnaos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2wpfvbhib.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2gsaqjuir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2brutieos.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2vvpszxxq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2wexwdekt.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2frqqtwsv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2fecdltet.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2nypcgauo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2lbqdysec.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gt2ostrwvbm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2amytqcjb.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2xfelthhw.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gt2zngrpcxi.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2lqmshidc.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gt2jtmhfexb.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2lvtmreeo.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2bcnnvwpu.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2vwanffeq.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gt2fquqwjea.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2xwbrvsfi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gt2juyuqdql.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gt2iskypcqc.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2midevnbn.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gt2hailmxgc.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2xntufzpd.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2lvosngdo.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2hznxfkkl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2gtnykptl.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gt2gzmgsjwm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2whblkriw.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2siuksjvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gt2oodsazwo.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gt2huqveccq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gt2qzsfcpid.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2stmkwpzr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veyzhvog.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gt2yqyqbdbm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2yidamftl.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2uromzuzm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2vobvtjpl.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2yzwapyvf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2scvsraie.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbsstfzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2nkzueldo.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2nkbnutqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gt2mowemsme.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2ihhvcveh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2npnagffp.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gt2zhsmtfas.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2ipvcmxll.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2hbzyhrqw.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gt2jhdzhayi.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2tnhstmdv.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2srohqsiw.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2ixmsmuav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gt2eojvsgkx.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gt2dpmelwop.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2cgrrwdyf.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2pzbxuzvg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlcdvmwj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdowmww.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjosvvkc.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2quygyzoa.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zbkwpsfs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siuatoks.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2cgzbuxkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2gqcougir.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2dvfwquvy.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gt2firskddz.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gt2jovbzoch.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2rkngcpep.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2bgemawdh.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gt2qeatlujt.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gt2atpdtzeu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2lekvahoq.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2legzspty.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2qftjmznl.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2cokxihuk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gt2iofgfbmi.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gt2sopxxzbh.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2tufjytoz.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gt2omwitgav.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2xixwmjxv.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gt2aahcmroi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2cgvlgaev.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gt2emeryroz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2wjajigvq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uyyyqxkp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2rdvfgaqf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ecetckkj.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2zpvkznso.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2lwsdmidy.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2wwlaykrn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2ntkpjutk.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2xlhdfohc.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgjwzdsb.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gt2kevdokvc.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2xpiukbua.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2gwqsdqiv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gt2qvbpdrgm.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2hpdnfpdg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2rqjkmlvo.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2nvvdxbzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2ovqsxeka.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2ilbvsebh.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2rljawcqn.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2kqgprdvj.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2ijytaejr.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2wcmzfjjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2stkbxjca.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwwhbsrc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gt2gxokeypc.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gt2tgbkgfob.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2xerkxenz.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gt2boubryzk.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2kjuhxwsh.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2lexjdbwe.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2cjaiogmj.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2ahjryzcr.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gt2hqeurtbz.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2bidgzhfk.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2qhzuhbkw.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2uoktvoyp.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2sgffpwsn.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2zhukhdvn.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gt2basyslib.html


<!-- 参考信息 -->