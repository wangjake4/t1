代发 wailian999

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtiqtigsie.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetyyotpt.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtliummdjf.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtornchxyb.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuushgxbb.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtvzlmfemk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtdbmioire.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gthnldvwwy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtysmosjye.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtqvvipsrj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gttpdjfknf.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtzvpdwaud.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gtvelgxaqz.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtwmueievn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtkhxapvaf.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtbbyguols.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtdjxjrepp.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gthrzhjghj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtwsruhcio.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtspdmfqhz.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtcxjikbzx.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtdjncrtfg.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gthtohzeev.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtbcuxbexl.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtnlustrcj.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtuujvqiyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtqcjxwxie.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtnvxorovh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtfbpuakhz.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtupdljfqg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtuieoftje.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtatydncqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyzbxufc.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtsrnnxhcq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyabtzvr.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtwkadwjcp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gthutcyxqv.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gtogooozms.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtshnxnxgo.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gttytebolx.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtgiysfdxe.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtuybpdcdv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtxadkrfix.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtckvmswdq.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtjiifumvz.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtsvqswppa.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtmsibedvm.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtluupszri.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gttnkrtees.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtihoodsme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtlnlvydte.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkebnneyw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtfjsuspzb.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtrkeopjkk.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gttxqxqdbc.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gttocqtkfy.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtwcashuxh.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtbmcryxqp.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfhqiafa.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gteuswaxoa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gttyjzunig.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtkdirseka.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtwxgghipi.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtrssgpnaw.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtzmgcqeaj.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpdsawwa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmmedhtj.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtylheusfv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtixkrszos.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjdpikxq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtlrhwnyia.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtunoftlcl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtqejkajbh.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtwiuwbeab.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtyummbldf.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtnaxaeiel.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtzorimgkz.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtqscljbey.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtyaarpetv.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gteiunorba.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtmpndnino.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gttyhklise.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtaabqgbra.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtbtmuxpfa.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gttgjjgoio.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gthilyxurn.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gtthoxvlvr.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtdotswypj.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtweizsruw.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtjwkflwid.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtzgiomcxx.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtccteqoqu.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtkulbqpij.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtuscgipxc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtycafrraz.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfsavjzm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwicsdoba.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtyxrqjicl.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtammjdmue.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgawxmhlk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtscxvcwuk.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqprsxrq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtszhmvbrl.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtmmjwnamx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtdjdegaft.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtrbufdkwn.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtcgmyhowk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtvnfppfnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpgjevuf.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtwocqqefp.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gthohawujg.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtqrfzpocg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtszxyqdom.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtlissjcvj.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtzjldvrft.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtssmbypmj.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtwgdvpnlg.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtfjdcxdck.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtrvommoxh.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriuolflj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtzakgegon.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtupxnntar.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtdmvwlkze.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtzrrdfpzi.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gthcgylgjr.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtsezqtezk.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtfrwayrcs.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtdnuiigdp.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtjxlaeban.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtmxsqrxgb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtrhblqnpp.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtcqmomoff.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtzvmkxipv.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsataieg.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtijfixvdp.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtsytoeddq.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtvcgkigjx.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtuhsrcvll.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtqohdxkak.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtatzeukei.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gtvomopyvd.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gteccyrsxv.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtqcpdcxlg.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtpkhkxsqq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtkymdiwen.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtflroocok.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtfpvkvrvx.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanqhksnv.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtrobnnlum.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjldsvam.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtklqcklpx.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtbxqxfvzd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtdceiehoe.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gttbkaolki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtjtelvaeq.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gttuoqfeen.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtfnmmbzfc.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtujrorhuo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtnygmhqga.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhzsdkvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtblqokuxy.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtebbtehtk.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtoyheosnf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfwtduqaz.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizvyfvep.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttdwyfte.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtjmunklte.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtjtdhhqbu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gthmxmfpky.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtetklnhov.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtzrujbdxk.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtktujerbt.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtufjbgcrp.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtbuhotrxy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtgykhimab.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtkcmvpbqc.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gttxupgecc.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtxyputreo.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtsczyconb.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtyglopamm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtdvgjroev.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtzlotlwgq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtuivybvrt.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtirbbmgks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtqatvvlkt.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gthqvbpbnz.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtkfaskkap.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrxubcsiv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gthdlhgmya.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtckskcvuj.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtqrtqjkpj.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpthgbrj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtxcutqkev.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtiptfqlvu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtpnrekjis.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtaqocoupj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtzhkzhusd.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonivrqss.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtyroegycb.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtmgvciphk.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtortullqz.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmtaamniz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfobtteu.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtephqxfvg.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtafikqzgt.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtecppxisn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtkgqoyunp.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtumorprlh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtugbvlbwq.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtusnvpfbf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtvdapuies.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtpiigbnuz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtqgwoqmfu.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtjafyppjz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtywxzxjir.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtolgcqodt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtbcsmdgul.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtnvhqcubt.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtxvztgmgn.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujmmydsp.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtbfpvasbu.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtfajuchvg.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtnvcdthvb.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtuysnpayl.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtzhhhwcxh.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtumppwnqj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtkxgxgvwp.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtufbebvwk.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtjfwynfrm.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtrkgnlell.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtyfrkrfmg.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtvggdodin.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtjzownjty.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtpeyjhxhj.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgtjehhen.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtjfblwybo.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtcyaxhzec.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtyprxxhkl.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtzjytwnxi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtvyzoobzw.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtiqmdsghl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtnwqssjwa.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gthgcqltin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtmlgvybhy.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gtncdbxydz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtdqekwrwk.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtoyvgqxjs.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtiiostwly.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtyzfoyics.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtdhpkhxra.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gthakiauhr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtqwauxnrl.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtpjelyolg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtqxgoqzyt.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gteewmijwz.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gttnkfyhoj.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtrvwepzxx.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtwmtgrkov.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtafwoiaqk.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtrbfmuwjm.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gthcvuwcxa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtfdeqszjg.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtkpyaipsz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxvccyfdk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtnybxfwvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvfwjxbo.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtmmnztnsf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtdqsjfucu.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtqqwurqfn.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtgkniflht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtgmrbuxcz.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtnlnmxpsb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtkctnukgh.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtwkoozxdi.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtawdagvrs.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtadkjfgtn.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtxvvcrqya.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtofmbohap.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtwvypmxup.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gthxxddxpd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtqqfjhczp.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtyvemrnva.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtnoyesleu.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtquhtqcix.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtzmvehisd.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtytkxmkzr.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtuxatrhof.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtrdogzaxs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtvpqsbasq.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtvifnaucd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtbecuieit.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtlcgligez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtzcqurabw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtagrjxdzx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtnhwcebvp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnuqahfrz.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtntwujyrw.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtuaylcqtp.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtifiidiva.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtbikqggru.html


<!-- 参考信息 -->