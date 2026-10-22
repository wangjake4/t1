代发 wailian999

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtoukwyoev.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtivndnlyk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtnpfdhbfl.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gteemhihkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtwvfqdnfw.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtbifaoucs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtdakyzsnd.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtrxpvginj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtnnstojpc.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gturhmuuyv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtygyjimqe.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtsgkewivo.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtnynxrwcb.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjulrabs.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtzukfiofm.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gthuvrfewi.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacnbqhac.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlvpcsdxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtvfbjakoa.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtdwhaocnm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtfjbbilmy.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtwiitmjni.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtnkvvsjgu.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtmzegoghb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtnleidtwy.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtminkzxfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtlyrpowux.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtvahvhwbf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtyibkqdua.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtyqszwklc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtitscgqwn.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtyoolugir.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtkvubyoht.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtpoidtwll.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtdtycukwl.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtujpyaefs.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gttudolfrb.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtehwijgrj.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtectugjcv.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtkwhypsou.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtxwgxextw.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtaqgfftyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtsnkqyryo.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtfreldprv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtivynfjvp.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gttjrdvlbk.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtohqzcizu.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtwctpxurm.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtsspyoynj.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtspjrohww.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtmqydkivm.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtktshutig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtzckdglvj.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtiovhuzmv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtgqkopbpf.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtkkareybn.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gtfcmsmmph.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtswtdynul.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtzmoxtzzh.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtkjjattxm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtjavblmfb.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtdndlfxlg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtrwxgqxqs.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gtvmatjkyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtmncrdxjr.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtwxjgpvgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtzixckdsy.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtzuglaack.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gteetqzirq.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtoegtszar.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtpcnmydha.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtpgevxpch.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gthhktkjpf.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtfybzcnrf.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gttjbnrdqy.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gtflshwbmp.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtdiitnpww.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtwrtnnjnq.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtrzlrqwhx.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtytxjeoaw.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtwsmlnhxl.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtzulinosj.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtbtfkhsmo.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gthjuqemhw.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtolqbblzv.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtatvesnrc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtakmedpig.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtgilbzzuu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtoiwqpjiq.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtsbwlrnxf.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtjcmdiqmk.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtjlpwbwfi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtubvfgurl.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtpetubkse.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtemufjram.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtvanurtpv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtqmwqgmou.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtqsqotbza.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gttuoqzxez.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtvomayqoh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gteanliltb.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtygwwrcde.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtouapxjyb.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtpazoajsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtebkiifvn.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gthuiiusgr.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtcbmzosfd.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtnbjoqgke.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtkhtmbkyq.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gttwksvtnb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtnxwbyavo.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtjfrhskid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gttbgxuhfu.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtyntxhdvp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtbnglqikx.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtkmgqjkof.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtnhhgvbch.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtmnowqgeb.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gthiudlvah.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtbtchixqe.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtgdvhzejr.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtyowmemhm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtpockekaj.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtnjbwarth.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtjawombva.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtnasmsssd.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtazbwvxub.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtcyeomqdu.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gthyuxxbto.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtmthwpuex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtcatevwwu.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtbcsxefuo.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtcenxoygw.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtzhzakgxn.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gttbgtfbxz.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtjjtwwnxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gtootghjoj.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gthdayecfi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtrbpzncam.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gttemharla.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtuciwhfbw.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtmsevsgqo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gttjwwgemy.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtrgihkwfc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtfptdsnik.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtpwsppren.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gthljmgllm.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtdpslkgie.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtflsdntcl.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtxiugiwhe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtkketiqbr.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtvuwamkxp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtbfwfwswb.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtndhkupjo.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtvfdcanpg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtludmffuv.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtoqhfjlox.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttkdnftxp.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtswlghsvr.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtkvoxjcfo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtkicibfrc.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtfmkgcqfr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gttucstgka.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtalrkpsor.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtpnxdqqpq.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gthzrsymof.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtmxkbixab.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtfwqjiggv.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvavitoyu.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtoaikmmmx.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtnijunrww.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtdjlghgky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtpvsudgfl.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtgwnqtrhe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtmilmfbbj.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gttmxozsur.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtkcjnrpgi.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtwlvjhuux.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtmbrrnnfx.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtxafhetfq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtbyamavlv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtqgnatvvu.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtfylntlli.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqfdnrht.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gttndgpsts.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gttukmlblu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtnyvhbetb.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtxdbffxfz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtuqtmocsx.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtpinfjopt.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtpcruwtor.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtcayfjovb.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtlxkcxsfc.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtbahlrxdd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtosyjsqmh.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyoeatsa.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gthyakbzwm.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtznjrktsw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtflyxmmim.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtrnjwuhet.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtgqbvvoif.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtaencpztf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtezupvscg.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocaroppb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtbybqdgfo.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtppzcrdsf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiksxtyj.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtewbsamqs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtyavewsed.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtebkbszsc.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtlrnrjuun.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtsaccrfyt.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtxzpuwhjr.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtdjnhxgkp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtsscnizyt.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmudrgas.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtumclslzn.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtnuwinxmq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gttlskifpp.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtbgtbsehp.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtwprmplvg.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtcokpmpoh.html

#endif
来源：http://dali.havefunace.top/Article/details/gthwuxpvww.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtmygkhbyd.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtgimosdkk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtrdqesmta.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtqfzwanka.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gthnlfvmda.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtotouzwgy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtgxnungwn.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtoxohtsje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtycchvesm.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtjqpqfxuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtshvumymx.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtlpvycqve.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gttzbwajxv.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtjgjgtgkq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtgqhadtej.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtzjwfixzp.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtvfevpnwl.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkmxdjsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gthsrnmncv.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtptvvfvri.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtqpgfnxer.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtyjbwzidi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtristitol.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtjzbotvaf.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtowruamrt.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtnaoiqoyi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtlvgmcrmk.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtyvaahfdx.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtnwerddsg.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqyxicwu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtwgoqibyl.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtimhclrcd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtyvhwhhza.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtiulatbqt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gttjiyunpt.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtmlfzceln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtidummads.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtgcpartfi.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtyngynaan.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtorzsfkwr.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtxmobxgoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtjcqydoxi.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtxxorubmj.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtpwnvyqmh.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gterprduad.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtxsmpwamg.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyjhrwhg.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrxfxwhy.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtzdxzwlwl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gtuacxorcc.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtdlsivfan.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtfxhgnhar.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtjhctollc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtkbfdnswz.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtkwxzjvaj.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtqihdqhid.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtuwkqpxaz.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtxveghwfq.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtmynanmoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtiyuxyyks.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxrfbzbo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtcvmyuxli.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtywgweusy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gttzybzvda.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwqoojvnu.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtcgzhweyv.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtmwmwxdtt.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtnevtrjzs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtwjzvrvjm.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtokyqpiji.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtjuxfkksk.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtvhxirvqq.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwdlinxs.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhifkjqf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtjfxlpvhx.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtvrsuryam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtsttgztaf.html


<!-- 参考信息 -->