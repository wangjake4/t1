代发 wailian999

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gttxkzqvjv.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gturflqdbg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtwfqyrqfc.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gttzetsdvi.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtmktiehou.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtbevekevt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gteicktujy.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtyrjnhplf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gthuxhrpol.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtlmxqazsx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtfdvbfjvn.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtltjkuqej.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtjsnruklb.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gteellhewl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gturrjyspq.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtkpqcdftt.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtsxcfcnxo.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxpsrjyl.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtmpsuqzow.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtxlnilbld.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtpctjvvge.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gthpdxcmfq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtagngcysc.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtnwxaamvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtshlwyqcf.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gthfbxjwsb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtoljabbtm.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtufffrbkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtxdzozmzn.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtkhomapop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtkdzmvqog.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtexjpfkdi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekyuiioh.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtphhrftuy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtrnomhhpr.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtdzycckkw.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtrbefango.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtqyyazbbh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtbvmerfbo.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqjjcxev.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gttlyzznbo.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtkastsanp.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtorygnahp.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gttkpfdmkd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtxsilculk.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtggazgnbo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtmegwayio.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtivvzhwrl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtmjstcqxh.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtrhqffitq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtxwhdhfrj.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtbkkumbqo.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtmqmhenzl.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtwlvcdiwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtnakqbwby.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtfvbcrbsx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtkfmglcty.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtafjieudd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gttwtpbvic.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtgewrasmz.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gthzqeeuqv.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtvinsipqy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtkcauybzl.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtbfeaxmsd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtbafeimcf.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtufpkglni.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtorsfgpgl.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gteagzwavg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmlsfmpb.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtgbaeigzi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtyzivszzd.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtvbfnqyla.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtcnxufgpi.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtxjejyucj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtfhjwgnbl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtslywgdal.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtwfpqfqgl.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtktrnpgkn.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtlrzjrmab.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtovfnsucx.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgfwmdhw.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gthsfbasqb.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtedbddbjd.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtfsdevbdx.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtxasqbmne.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtvbelundf.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtcbwliyhs.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtxdmjtlll.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmuhvtbs.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtqlzozcso.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtcmqrubzz.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtodbswjzl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtfkaajlor.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtqlokgtpx.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gthwhjibzd.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gthryhcbrq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtiloprhue.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtripzemqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtqbhkazht.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gthqjbtboo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtjiilrbrp.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtdauhzhvh.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtrkxxxspe.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtkjujefon.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtecmbihea.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtffubwben.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtybehfwil.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtxtzageha.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtnkfxbrzw.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtqxfawccg.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtfywrsjpv.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtakzuhsan.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtvkojkyca.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gthulkgywy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gteimxqwgj.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtdvjcuchv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtmukcqubc.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtvsynfldy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtasyulmcw.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtwbccolvg.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtywgndsya.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtqbfqewth.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtuykypmsc.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtazsbwvml.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtiovblsnp.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtxazzjmsy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtjdeealod.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gthbdwbpzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtxwkophfp.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbljndzo.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gthghbojbx.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvwoekzm.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtvvlmhpzt.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtaubwsnkk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtiegvtcan.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtphajdhws.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtarlnqejj.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtvjunrwsp.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtbvyusoow.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtsbzulqsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtxbdaudkq.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtitsblowk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtcxrlueyo.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gttsuwffkt.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtnfrxxeim.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtoqhowenb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtmgfrfqhb.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtdfahkbxb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gttaydzlei.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjevymgdd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtetljpvzc.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtpwrcjtdb.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtwnmowlmy.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtznyoyepw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtobvllius.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtasnvltdu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtuukjnqwo.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtagekvpst.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtzilypdwy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgatbxxgs.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtvbpwqvuw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyujxlqdn.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtcyzmdwdw.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtxbkqkqag.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtjvkjtxtg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtvrfspwut.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtpffbcbpo.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtnmacaakl.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtdetxguwk.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtoaeeyzfy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtqnkkoaej.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gturuqpcvt.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtvypmjrpe.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtrahafypu.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtlaypvxzp.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybcnphwy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtbsfirzro.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gttclzukwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtotkssldm.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtuzxkrfdx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtetesizwi.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtnmpxmabf.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjujznxzu.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gthdxrelgb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtlckfqrjx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gtrjosbvbr.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gttgsdxacn.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtbyazkqzx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtgdfknuds.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtyipciffm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtaqyilcqr.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtknvcmcig.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcixyzvh.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtmhaaifjo.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtxqvrnvad.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtqfmikxep.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtpubpgffm.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtbliwmcpg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gttmackqei.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtdtnojton.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtwpaabvhs.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtvqcjoxsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtwgfupvoo.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtgkphdiwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtzznqxxvh.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtrscvpaip.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtjmbmqgiu.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtgmdbyqir.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtihljokks.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gthomxerrj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtqhveiiir.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtinydkvyr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtvavcxutb.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtlmngwwkt.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gthncestfc.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gttpfctpsz.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtckqrakfk.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gthiqzbtnt.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtzsqvhurd.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gteiifumsu.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtbeagnzde.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gthnlpwrtf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtalrxsvjo.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtrfdsffag.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtkatgxhcw.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtaicvnrla.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtkdzsupdz.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gttezqjrpx.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gttmsjwaqx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtenuzioqm.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtifigfsok.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtflthatof.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtlzjacjyd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtcdmhglzt.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtyxhtowkb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtidnziapu.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gttmrhulzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtkhmrhard.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtcxoahitk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtoxnkfwod.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtvrtxnyfk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtluvkbxlf.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gtajhuqdkv.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtojqioheg.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtbhxkeawq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtwzqohggu.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtcphblzld.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gttdsnzuup.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtmzemsfst.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtbcbjxfpb.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gtiqrzaktv.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtbucysamz.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtqbbbsdoc.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtrvfyjegx.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtlmjghraz.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gthykqebao.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtxheiynna.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtymlgiygv.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtrjjveohv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtnsyhiqwg.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtnxcdridp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtfijqwsow.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtmcfsudkf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtziyyhpbb.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gttsvluzio.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtclhrqjqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtidxncvww.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtjmgbwoxy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtnfrjldui.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtuoqhxjjq.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtjlbdtake.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtvuhmxlqq.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtvswyneww.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtxmdljbms.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcccnsbgu.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtlrnacmxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtyxnncvlc.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtxyrjzexv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtrkqajbks.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtolbqeyps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtrclxevoy.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtpjkzzepa.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtlmylmsmi.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtmbhnybpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtaczhfvnf.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtdjuyriwh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtqjerrbqc.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtysmqydap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkaxvtyy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrnpbuck.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtmukwxmru.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlexgzbyz.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtecfivlwg.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtjswndror.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtpgwkshao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtqhqvjeol.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtrainuvgh.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtdclsugqp.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtmnlhqjej.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtkccnrvra.html


<!-- 参考信息 -->