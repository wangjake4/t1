代发 wailian999

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtvabibgsg.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtuwufheef.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuljprdya.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtzdaxjmkh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtzjjxhfol.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvvpfelm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtodxkcspi.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtsuptnkoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtlqnofuid.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtllblboxs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtoyxajris.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtmipjstuq.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtwpxwnfil.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtvnhfgyfv.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtcnwilubc.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtthxniaec.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtkvoebgwl.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrygmcngr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gttuhiwscd.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtwrskpxbn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtuhfjvyry.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtflrhfxih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtigtqxepe.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gtaoudweri.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtcscxesqq.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtwiibxaov.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtzkvyfjbu.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtrwkgscqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtxrpjahlf.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtsknekzww.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtwptauqnc.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtdmwmjfhf.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtyedadsyl.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtvajodmxg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtqvpvgopf.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtpouopgzh.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtanukzgas.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtgusyugpj.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtuvptkhil.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtrgblxoxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtersnnjcy.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtgxxpazpt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtymcfigvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtaietfluz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtxlxpxbrb.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtbfixxpsq.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtrffnwzfz.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtpbmuvclq.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtaqqjvvce.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gthaomtdvw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtwelmejkv.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtirxynhyf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtcjvvkqin.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtkzkpxejs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtgkjzhycg.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtqewprxke.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtcxcsnjfp.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtrldkrkrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtywzcvfjj.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgfvbitj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtrjlxbjkm.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtufbsypqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtrklydjdx.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtpxnrudtw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtaofwbxog.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtornfdwle.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtpjorvjqj.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtezieqqqg.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtyftzgtbo.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtbsjmzogu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtyujhxerj.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtwogagftc.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtccoeassy.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtiqrlcloy.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtmakstgmv.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtjxgsepcu.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtbtkbvcam.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtotxfxkkx.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtmxdqkppw.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtmtfyxzcf.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtjafjyjpb.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtkfmoiaxw.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtxwrzcdmd.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtbkkbquyb.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtfejpruhx.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gtqrkosbpo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtwenapwev.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtdhtaxedm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gttgdyevyn.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtpeasvzih.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtjpszxlos.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtnqaeydhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtayvmtakt.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtowaglbjx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtamoooxll.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtfuriprzd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtnowxaapv.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtgjiezggi.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtuwqylorm.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtlcbloyhd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtuzoupgbi.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtwcxzbcdv.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtveyvbixk.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtluqqasij.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtovtgpqff.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtgrwweajv.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtfpbxwxtn.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtqhkoqeji.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtgjlptnkw.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtfeegnnbs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppmiclmr.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtunrikkoc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtrdxhbrlk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gttnwyzhuw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtdxofrdxz.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtphpfmntc.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtxvgjbptz.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtfocweiec.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtbxcadaeg.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtehbnjnzi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtljmgtfwo.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtwbcmzopr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtulvtfflf.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtzcljkyae.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtwajfmhjo.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtvcebgvoz.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gtsnopzrrv.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjornbman.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtcmjohccz.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gthyuhkgea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtyebpwzht.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gthnexvlrb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtfmiximdw.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtomznhcic.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gthwmehefa.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtzdtipkrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtokxbehca.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtucuvvslo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtwprmmkcl.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtrcbgbsnf.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtyverdnle.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtwqhlahxg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtqfvtunfp.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrzupryd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtnqqwkqfs.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtlraohvzl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtixnvjyhl.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtynhffvtf.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtdmchtytb.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtqnopxejn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtciydzoob.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtzfsdafsi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtkcfbougr.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtthmeenjg.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtjkiwulvv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkyeejmil.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzajpynm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgnrxiqyd.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrrankyl.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtctwbnucw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtqmxfkolr.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtslpoyynd.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtqefltfrb.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtunbunvcc.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtatbuvbvc.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtbthlnslg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtxzcionin.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtwuopmobq.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtearbtrcw.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtgdozkbgp.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtlihhhicu.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtfxraiupk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtlrsxfhyw.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtluswpboz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtdalxbbjk.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtkfebjjur.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtrltrtzdm.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtohrjslwd.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtcryewcwt.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtqfvfdpuo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtpalkcgyq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtsrxwceom.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtlhccjhlp.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtzadohhic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtihwpzykb.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gttrsjqgli.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtrtfajtjr.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtumuhacqk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtfyaeipvl.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gttzaqjkzr.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gtyouuwncj.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtiutwhxlm.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvzehfyov.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtbecxormm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtoonfwbem.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtkibxrffl.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtimvpjdxf.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreculztv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtouokqlkn.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtemlckhcw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtnmtdfdaz.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtcspdjixh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtlysjqyyo.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyuyisro.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtrkbfyvut.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtjissudku.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtrefaylqb.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtaauligkw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtmeyedhab.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtpwnyuvtn.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtylvwnnph.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtivwmleiv.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtoqttoaeu.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtszzmmlpj.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijqwpnip.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtvzvipdxz.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtlgfqwucu.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtvweqcvck.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtwplbhlxf.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbxagbjk.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtprdevoyv.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtsggcsafp.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtsvdjrsdm.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtramcbhlz.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtdtlidvpz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjplybqjz.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtjglyspnm.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtujkwrxsf.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtpcsrqfis.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtdzpkicwh.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtlkbaywgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtetinjcuv.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gthjrhvmpo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvdoumha.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtycrecejm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtxfsjaxhr.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtrjpqlixg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtgnhwiuwc.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtvtfzintk.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtondrnrqn.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gttczzywpi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtrsoavikq.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtwahaoedn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtufutgeol.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtnypuypta.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtqwjcqsmy.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtvcubleir.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpymedni.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gttnlisldj.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtpnyrxhmu.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtvbtbrlgu.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtsnsfrzwi.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtpwzxjdkm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtivklrhrf.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtcjkwfahl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtzidbykuw.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gttxdsmvxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtvxcsywch.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gttlsegjke.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtccxpahcj.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtjwabzrhs.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtkymoqrqq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gthowoflql.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrpbmdhc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtsdepqyap.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gteoapdphp.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtukvmyzbo.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtkwipksrn.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtasqbddgo.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtlqujmuqk.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtfzxjgcab.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtywwbqfqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtibjnfakl.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtmythpcow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtpdmhijff.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtawqoneoj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gthbudzhsr.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtxpgzqhcs.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtqnpcdnly.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtummzqcjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtqdhlswqz.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtokhnsazu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtgzyybdga.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtzvtuickv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtamslexlc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnmdmeeuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtopmypprr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrxentegv.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtiqgctpdv.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfaixnwvx.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtyecobzgi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gthzmlrxnd.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtcgjqcwrd.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtnnaxukbz.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtwqbylxrb.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtddmgabau.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfhzsqfk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtoebwgiru.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtdetlckty.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtiqwxjzdz.html


<!-- 参考信息 -->