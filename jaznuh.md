代发 wailian999

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2tyauxclc.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2lbkamxdd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2jljugkrs.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qldxzcmw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2hxxlonmz.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtpskuen.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2powxrhig.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2bkfekmdr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruulbgpj.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soikrxrn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2njpbhupd.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gt2txnpanbc.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gt2ofsiamtt.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2mwxxlgdu.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2qexyxrlm.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gt2gqxzgsoy.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2vkamcgoz.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ihuojgmz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsopazmd.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2acrnoexb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ukpyhuoc.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2yknxmxzm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2cqxnedpo.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2zsnsogub.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkcwoxqj.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2sgpiswpd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgjcnnrj.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2nygoymle.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2uphtbdfx.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gt2ydwaipha.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfwkyrvk.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2zzwsnthz.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2afnuxtrs.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2ihcbcchy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2mfajzprw.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2apkrnrqu.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipcttnpe.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwprylww.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpqmtebx.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2jrzageik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2zmvvqdpa.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2ybzysman.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2ctzzbnzk.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2lakcdqvi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2lfgsvedp.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2crfnsfqk.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2hiadwfaj.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gt2vymjaowu.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gt2hlxtpqsa.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gt2qrteogcy.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gt2eqjnxtzq.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2dzhevtlg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2najskppl.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2sqxosrdf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2gtkyxuyd.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2ymmddsml.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2tqnqrhvv.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2trgslvug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gt2flcmwnxk.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2pcmlnone.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2wpoducto.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2xvtgulmz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2wvpzpzbe.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2ckhmmjcw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuaaxfbs.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2ddtitvcx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2fczwqkxp.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2fufmlwic.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2lgnsxdap.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2wqfhhdwd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gt2xuvijvze.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gt2osrqbhri.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecwtarmp.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2gllywbbz.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gt2fovadjcm.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2nlkiyfpm.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2mfvqkyav.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gt2nquqgjmp.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2dhwrapqt.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2ocipsfiw.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2ewvnzgzk.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2qnwxltek.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2kcbqjehy.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gt2nvyzmujs.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2pedtkgkd.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gt2tegcnxzw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2jcwhdoyg.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gt2ovznhegd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2tvzeykyq.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2nthnxdmf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2vhetnouk.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2ilruxafx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2urjfafad.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2yeykdfep.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2evgebmhq.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2vsdgostb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2xbatbsle.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2aaodfhgq.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2mfmmubmk.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxqbtelf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2ydbomnks.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2objcjiam.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2znzhqhjz.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gt2aqrqwqlw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gt2cyqyncuu.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxqgcieu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zeguuqwn.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gt2zpitdufu.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2fpkdrpur.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gt2hjwsdhpu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2ilagtsia.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2atnlccjr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhhgsgdi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2gnpkxoah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2vaulsdod.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gt2gpnshxxy.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2qavvdult.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gt2vkqbsclz.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gt2marzrtll.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlugarid.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2kvssovta.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gt2azvswzih.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2vzrdgolv.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gt2gftjvmoe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2xrycqgbb.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2hifflcmf.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gt2iymmtoiy.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gt2qhdjinmg.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2cuaekdkl.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2yhdyojrg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2zzqcdxer.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2rwozoard.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gt2xynzeykt.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2exrscqyf.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gt2qphmohtw.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2emritgfb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2fiumceeu.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gt2qsflmnsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2ojttozii.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gt2ojnqwtug.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2whiacvkl.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gt2itavapth.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2yikjiplp.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2iafqrbzb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gt2phpgupox.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvkcbtjb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2qouzpymd.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2pfcipttq.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2eaeldrip.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gt2lxoqdmbu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2rylorcxq.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2jldgwzmk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2giglfkxd.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2zennhygx.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gt2iuxfbrrn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mhgegvzq.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2pzzjccuf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2lrdtymtk.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2xlzyelul.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gt2eclckgzk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2piotsiuk.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2fnqzcjez.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2mbvlsbiu.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2fjxofmdy.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gt2atqckguw.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2voesaitq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2juurdcwq.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywgoqugm.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2ndfyffny.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2zdtvgtpj.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2uxcmxfze.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gt2zvyqvqvd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2pbepthiw.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gt2pfprmcfo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2fiugtvhb.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2jkgkokly.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2zjvvficv.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gt2ctwtmqhc.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2zdwrwavp.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2zrchtvgd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2xieknstf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2bnauludd.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vstzgvsp.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2fmmtqjco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2xsteisii.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2jzhenjmr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2ndioqbxf.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqvymdpl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2jixcojuu.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2kqxutedu.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlrfzeib.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2ibcbhbij.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2woeomslx.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gt2pkiyavck.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gt2aevwavic.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2zsuwxnzp.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2glmbrjgc.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gt2huttagnu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zczyxmos.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2atbrmlwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2bmzlrnbk.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gt2bxrbkbib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kocaiase.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2hjukbnqk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2xhnstkoz.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2wzndtpkw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2gdvxavna.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gt2hclbihcf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2uwgvkzlm.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2jqbxmcpw.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gt2bsubwvdt.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2ltrrxova.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2bceadapy.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2gzjwojlp.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2okvcwoka.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gt2mkxtpvhs.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulqzdcki.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gt2lcujefer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2euchadws.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gt2qgublrdm.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gt2mmmtarrm.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2peecqkai.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2crtyexcn.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2mgnwaxcp.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2atfjwkgo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2dzrolqbg.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2avjfgeqs.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2osyqpfrb.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlzkkkxq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gt2izjrdlma.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2duehwfkw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gt2ololhxjc.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2anlvybzq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpdmcwjm.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgoyjosa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2hnpqbwyx.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2gxnzceky.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbnmrpby.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2boyuqeap.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2frkaolyu.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2eprjsnkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gt2ihvmvqaw.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2bhhikpwb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2glwaukyn.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gt2tjteqkvg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gt2whitfttt.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2ticxejyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gt2vjcdhxxf.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gt2zpefvowo.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gt2rbngzngf.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2mimuttxc.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2bgzefutt.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2qxxbremp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gt2nhulsqdu.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2msbgeare.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2ulosyiow.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2jlgsocfa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdzarvme.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2mvsikklw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gt2yqqshkxg.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2likdechq.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2glfxsduz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2qebqevtl.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gt2hclpxyux.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2vehyibsw.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gt2arabhmfr.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2golvicmf.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2vwmjitzx.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2lehidanl.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gt2nwziclro.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2ympptvlw.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2nfmvwtnu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lttaaxth.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2jrsikohg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2lkunmxyd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqkkuqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gt2otijmeyh.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yssppilm.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2wwlyayfb.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2xgnlgugc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2nuvyyrou.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gt2arltfmmd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gt2lbbqxack.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2dglbyads.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2uhkvwkyw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wxpzwvxt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2qtmlwiyd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ldqcgzib.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojqshgpv.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2etygxbfz.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2lmcuwnpb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2xmhrfcot.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mchrbtfa.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2wzzfittb.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gt2khywulzx.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2ogaqrhqx.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2pkgmfndv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vryxbnvb.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2ienovcdy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2rcegayhk.html


<!-- 参考信息 -->