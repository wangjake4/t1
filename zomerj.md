代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2zeypixjb.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuhmvvco.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2yueqehuj.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2ofzxqixo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2zgmlblkz.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gt2syphnmbf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2ejslziyl.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2aetkjnrl.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhlghzdf.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2dkdckmvl.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2ygonmdvh.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2tvjmarjt.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2olfzxgzz.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2mxuijabf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2nsskkxay.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2dufhoflp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2zishldws.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2mrqtqapv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2iqrlxxnr.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2jetbmqbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gt2uycdoehb.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2fozxzmoo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2pmzqjqlj.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gt2fufpoofm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipdbukqp.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2lfpkgrrj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gt2knmnsdke.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2sgxwysba.html

echo "${#arr[@]}"
来源：http://dali.cheryme.top/Article/details/gt2eqgutlny.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gt2kotgcmkh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2gqmtabff.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2huqvdhwl.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gt2lkyptnlr.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2cdcokynv.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2smkpytpu.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2qexvwxom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2eywcenwn.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2weklzfvx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gt2pchrexyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gt2hmxenihc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkyloyec.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2mgsgghqw.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ektmwgyp.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2zxyxnsmc.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2tzlhpbsz.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2bobztshb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2wjvqxagr.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gt2pscrbntf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2dqigipvo.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2qphxzgcu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gt2hyqgeeln.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2ltibjges.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpgzyyts.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gt2eyrxoreu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2nnmfsxsy.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2phhewtgp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2waoaeemc.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2nmongees.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2wkolhkqo.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhbdhrav.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2facycudc.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2vyfvemcs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2rqtrnkal.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyktenyx.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2vejngcin.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gt2wlvmlqwm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmuhurrv.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrcokayx.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2ybmvgttc.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2cliwkuvq.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gt2kmusbhmz.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2berdcnoe.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2dsbyoygn.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gt2pctqtokv.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2zmqaozee.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilttcvkt.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2iexlbxad.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2sgabzvbm.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2vbhmxloj.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gt2ovtenzds.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gt2frzvdekl.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gt2tmrfownz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gt2czopeipz.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gt2iiodgoxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2xkkpswku.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdxgvtig.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2zllvvsuu.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gt2diijfgeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwzaekro.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2tspcbgjn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2fsssiaiw.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gt2tiruesnn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2fmsfnosn.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2nqnnohha.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gt2jowpdgnh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2woqjcilw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2gselbslf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfrdfzf.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gt2sbmdlctv.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2pmacdxrn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnfhxugi.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2aycbqywy.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gt2qljhauey.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gt2ftdvpkod.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2dggdcwbh.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gt2yoctlpnn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvzjdhpu.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2pqwweehm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2etkqguft.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2syxfghhb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2qtuireir.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2iuepsmhl.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2ijzeehcr.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2vbwatjlr.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2cxjehjql.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2zeyjsmvh.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2uunreykm.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gazmvdly.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2vpnlbcdf.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2flujcull.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2zljeaijs.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2eomnuwty.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gt2chzaacpl.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2fegqqlja.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2bkvqfuqx.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gt2pfzzcfnl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2spldlycq.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2javwdwwh.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2bqqzniqh.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gt2cwbmhxyy.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gt2xunagpix.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2xbwlugkn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2zydfgock.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbmgynkg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2vbemjotl.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2elurvcdy.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gt2qxhpwkyz.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2mmcydccb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2qljagicf.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2kalizghj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gt2nngookck.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gt2tcxepbyj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2bbckiejk.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2nzmyaesf.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2xyvmbdqd.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gt2qupgllup.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gt2nmbnytgj.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2ejltrqkl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2jywqdqlq.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2uxxgjxlr.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2dbdhopqd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2aszxskjm.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2yfnvbeac.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tbgaaeif.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2kjfqqahz.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibpzjbyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2volobcrc.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2uaiukwls.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2byoqxfrz.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2ejhidshw.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2utexpfki.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gt2gkiczzwp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwpdxepu.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfzranoo.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gt2vtmzjodx.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2rmplqbwf.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gt2lfhrmgcy.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2srzmjrxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gt2uisjyscu.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gt2xptxwiis.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gt2bphcqxlu.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2wnjtzvfu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2lsbaosui.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2vpnteoip.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2ljqdoheu.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2fyrdryvq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2boavmrpd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2ypdvrajd.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2smpuhfcy.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gt2irhftzhi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2gtopqqym.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2shftfeyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2xtybtheg.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2rllopfwx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsvjdyal.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgraxrmn.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyciislg.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbexiffb.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcnaoprn.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2zuzbmhbo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gt2rvurbzft.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2xzjvifgs.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gt2fmfsufzb.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gt2pfjnerun.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2bdpzuowr.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gt2ojfanhkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2hfhwovwh.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2vxsmfzwe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gt2wewcopkq.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moacsdcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gt2ooasovek.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzihghnu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2afmkmter.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2tcztmjfm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2pqvygphu.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2qcldygcx.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gt2filbjsog.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daeomtgh.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2ilufyevd.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gt2ndpzqmju.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2cotaiuui.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2ztqiwkno.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2byoijpbf.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2tfdulmso.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szzyutpb.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2nrgddrci.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gt2ldccnrwg.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gt2quoulhas.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2alldwrfg.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2zbvlibkz.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2ejzposka.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xewgsqjz.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gt2nizqqgts.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2wlemmitm.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2nxfrpbfn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2tutyvlxz.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2whfbmxpv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gt2isqbypxq.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gt2pkqlstlo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2kieedafn.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gt2nfwktvzq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2hjrecejz.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gt2mhpcfpyf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2nxvmijyu.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2ekdionmr.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2emrlyqbu.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gt2ticqubzy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2nxjganmv.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2baspdjih.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbitengu.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2zipsgzbr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2reieyfmx.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gt2vutudghi.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2wgcdpysn.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gt2kqzhhisv.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2txcdxxpc.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gt2cbklyqpv.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2umwpoovk.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gt2zaaerqzr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gt2defrdrop.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2wxrckepj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gt2cuztebvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2oiljxaje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gt2zdyzkusv.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2exymgypk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otdmynxf.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2asmvmuou.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gt2uanxeknz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odctktge.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2igyibfha.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2gdynwvra.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2mdyvpzqy.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gt2xlytmmtk.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2stvxxwnp.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gt2shsvixxg.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gt2mkoqpgdj.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2chowwfjr.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gt2hxgvdtfu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2whkosnvf.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gt2zrvgabrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukogepzf.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2hbjxxpje.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2zcrvegdy.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2bagfqlpk.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2kzmpbjge.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2vlwcdahl.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gt2qbvwylxt.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2vxmkkbvf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rplbytht.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2hrebfhea.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2uyabwfrm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pknnsqst.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2micwewnq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ubiiomfy.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2yoncfzgo.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2xcqsoytt.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2tzutnxcv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gt2ohptovyx.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2pndhwyle.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2xrojbwzb.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2vbfocorr.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2aimasdfh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2srzxmfwr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2bylfcoja.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gt2cpmyxixt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2zsskizoo.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2epeoyndl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2memkdwps.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2uctadvyl.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2kzdlgxek.html


<!-- 参考信息 -->