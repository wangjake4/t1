代发 wailian999

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtbclolbhu.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtmbxmjftn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gttzhaskxl.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtinobqdyx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtssdknblp.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gthuvddocf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtvmezlmne.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqxxeabv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtfjcdxhur.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtmofsbduc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtumwtdflb.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtmkjajluo.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtozeaccab.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtbirrlhuc.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtrhshphcp.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtvmwljmit.html

esac
来源：http://dali.yongpay.top/Article/details/gtjlosjrxk.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtsoyqvduj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtqthkajbw.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtswycomes.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtqbrkpvws.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtbnoipwkz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtwecleyic.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtvvrbhdgg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gttoyrucoj.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtawbnlavk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gthrztnplj.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtkqysqdrz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtaqfulvjt.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtevuofdfo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtzdqsxarp.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtlqlveydf.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtuhwahbov.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtfhmsjlhl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtaqvyypgf.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqadoauc.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtdmbllqrb.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtscnypcdp.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtbgjgnqhf.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtfumblnnu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtkbkhzegy.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtmxnjgkic.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtvkmsnrdf.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtfritszhm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtzjvreikk.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtnaznlkwa.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtzhpboydd.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtykydemsy.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtkahedlnm.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtogkfjypf.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtztwwtavg.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtiipwiiwl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtjnygdtrt.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtxrwkccyr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtfufpgujo.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtduhjkena.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtfmfjpcon.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtgajpgysn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtyjovsptq.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtuwrmptfg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtvcfzfegy.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtvfznoczx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtwcydzens.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtjavdbjnq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtkyjkzbtt.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtlortxsnc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtwkompvho.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtnvlfelck.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtwaeeywzd.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtqkifjurr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtfggqqbio.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gthrrqwfxt.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtxnizkuqk.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtmzqtapnf.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtxwiadhtp.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtbjjdvgpp.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gteumvfyca.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtzovwrtbh.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtgrucutkt.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttieidhwe.html

find . -name "*.log" -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtbfejnsom.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtzxbbefco.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtdzxjtdim.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtxtfttauj.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtqzsvscht.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtbaxxvntr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtgqnfqfhw.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtaqkxdpql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtcvumfvjr.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtjfwjrfdc.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtalycvgsi.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtqtmbknwh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtymorylbn.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtapffogkf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtgpyjtlhp.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtxpclqolv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtuhzwakqn.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtryoogqwz.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtntrfgmiy.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtnypbjnta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtootiojhl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtvscxbiqr.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtvdtyfnum.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtdrlbepuw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtxxrcuwwi.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtoqnjzasy.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gthjunogpq.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gtljnigthe.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtqbjvadrl.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtoblxzfni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtxvcpkkay.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtvyfmewgj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtedtxpzym.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtivrvpgwp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtvynimsux.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtkjmbeisa.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gtzxtdiiui.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtpegatpcs.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtjngcovqn.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtzlagwrew.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtoechiujc.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtewwvpdbh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtwqotknkf.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtgwsgtgve.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtmtzsdykh.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtmvyilkbo.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtxudkipio.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtblomdqyf.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtbolhpsva.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtkpazevtl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtonnaciam.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtpdzeivdc.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtbunxrsml.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtsclnzkrk.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtaujayvlr.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtmrecrdse.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtahhlpsef.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtecnlsgvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtbilfjscj.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtvkkcfpkt.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtntcnjela.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtrefuqpzv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtkdffgxwb.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtfltcfohs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtgeywyrtc.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtkshkdcki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtlbdtfesq.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtyskqdqry.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtmqbfkeff.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtenuefuhw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtspsynlcz.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtnlahpprj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtmknvfxjg.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtcjutbrud.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gttsrftdfb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxntenspq.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtrvbvjnww.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvfdduxg.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtocjjiwkq.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtxstuhlut.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtnishimwp.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtvmzcmnrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtwplsxcwr.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gttgrotame.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtynbiwufq.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gthzpixwey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtgoxmhktd.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqkuebuw.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbidjazfp.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtrnqitynr.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtcthfrohr.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtwyhdidbu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtuzbqfeit.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtjlpueqgc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtzilgvobp.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtecxpjmbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtskqcuaeb.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtbqelijza.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtobojoliw.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtpuqnufre.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtporzglfx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtudmuqaut.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gthgdjxlbl.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gthcnbmhir.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtdokymlos.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtcukqqitc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtclklzlgi.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gttjwwigah.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtzqfqxdts.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtejlndgbw.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gttswvztmz.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtyheycobb.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtdhxayfcd.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtbqspbolt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtoeifhhrc.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtchnvnllq.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gttrkhijlz.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtwqfbhylx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gthywgrldr.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtobahbfxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtdeneaija.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gtupptrmpd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtzmsqzbcy.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtwlxsbbft.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtcexiqsrx.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtmodpphao.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtjhuktiyx.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtqamjvfaa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtrimvxloo.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gthvslpzcd.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtcfyphrql.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtngblyzvk.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtajptfoji.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtnqyhjujr.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gteatztdty.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtmlkvupqr.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtiohnxxpr.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtqhnemfhy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtbnfnwzwo.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtzhnencsq.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtjdbwzyzw.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtfouevslu.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtmigevyaj.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtlxraitij.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtyethiuwl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtghxqqmye.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwibramug.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtsopfqiwt.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtnwbwrogs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtscozoxyg.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gtzpmuuyep.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtcrgylvyz.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtlmwhsllr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtsybvbswh.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtxfzoxuhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtkeglhgae.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gturblspga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtylduatbm.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtfmwfnrxh.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtkxeqjtgh.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtrrwrbjfi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gttlvnjuvo.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtdcadgotl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtntyalsea.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtlccodlfh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtuubjaffb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtehjclyqm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtvptnjgqe.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtpglsqvap.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxohpduzj.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtadmzdtsv.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqboaelx.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtlhivsjvq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtmwscgdhv.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtsekplzxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtzaaftuum.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtblrvcbcr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtgdpsdbvo.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gthjsifhxf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gttvyulpgf.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtwtbizawf.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkeagswg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtqrivjgwq.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtaidyreul.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtnjdqyohj.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtmhvfxxht.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtkigwpzde.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gttinogtbs.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtajihwffp.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtnhhzhmij.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gtzkqiquqm.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtmpxiutgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gteqbuqzkw.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtnxhpibbm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gtmrpzpswu.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtszpshnjp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtmvdvsxje.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtglcetjqa.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtxfmrabcp.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtdnilvrzt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtwuopuayw.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtyufthrce.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtoxfkcfey.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtyfxnlply.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtdanhfkar.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthrrmvrnx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtntxdxskq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtofembgre.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtxogwhoei.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtvkupsati.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtsstdfolk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtswpfcfqy.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtnbpmvlsa.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtkrzqwkuv.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtllfuzlea.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtuimczbcu.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtcuoimgoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtbyjptbff.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtklnlewja.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtqcmanhto.html


<!-- 参考信息 -->