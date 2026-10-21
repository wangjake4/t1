代发 wailian999

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtfwjyukkz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmqatewdh.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtixecqfcm.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtouhuaxgh.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtxivpmfwb.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtdkgbczoa.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtecpsivqd.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtnlwabkoe.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtuhloygjl.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtohvjcxtw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtnzlgtisj.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtyzlgyywo.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtwwplgweq.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtvybdtxzz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtltfegcix.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtuxnwgequ.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtjdlvwity.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gteatmseqz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtxctmkrdv.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtqxdmpwfd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtjwfwhvaw.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtlwxafock.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtiqnnvpxg.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtnjwnkutb.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtrqmygqjc.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtndaqiagp.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtofcirkei.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtmzwtxbhp.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtntdtnzrj.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtzkbhxawp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtyfjqexcg.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgjkcmmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtnbucskhr.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtaujjprxi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gturmelijd.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtstczmkqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtklbdjylk.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtfbctzjtb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gteamqagep.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtwyeaxcrn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtbmjrmoeq.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtgqpnyrzq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gttgidfmho.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtfrphkxtv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtjhbxkpgy.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtywvylamj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtokziqyla.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtlimnjsmd.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwbjognj.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwmkjfpe.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gthmqnkmui.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqurjkue.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtalqtdgfp.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtvhhdkcor.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gttqalvasq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtqahfjkng.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtapghctdp.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtfcfztmdt.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtulnrdary.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtbthkoucx.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtmwhnugna.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtllnlrked.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtviegajck.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtdiisgtee.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtkvktwewo.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtejdwaopo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyodguqqv.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtceelqzfd.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gttbxonynt.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gtcsncrpui.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtktbkuyga.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtteetyemr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gthwjagbls.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtehfmwhay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyydmypl.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtchyfzbnq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtorndfuii.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtvocwfldk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtiorycwoy.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtnityscou.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtwgoavyju.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtlxpkrgnp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtujhekbtp.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gteeuxfwjj.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtizfmlrpk.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtmongphvk.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtuurlkwrz.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtinfvzati.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtxewyacfg.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtvzgfqrvg.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtrebtbphv.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtmgkcmkoq.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtdmqyttvf.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtfyckdtzw.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtjxczbhye.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtcoslbtlg.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtovdrbcko.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtvllzstyg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtdrfzlbfq.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gthbdpglvs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtwdiggcyv.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtcgsxdbvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtpihkwhtb.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtuopimqji.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtsqgopdub.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtefsxajcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtxuscefkj.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtvwazgppr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtejkkidyw.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtwweekzlh.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylifnkrj.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtqupznsuk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gttjsmcdrw.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtsvafsfqu.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtjmxttjsv.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtmminrugl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gthloadjfw.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtjlwjhohe.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtupbirzjc.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtlfbikyyn.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtzgmiqifz.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gttbseigmq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gteqjwcpvv.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtarvuplob.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtvikhlnwu.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtzwjyephe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtsoncokny.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtypngbwos.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gttnujjhej.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtlyiswoea.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gtykjdhmrb.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtysdwvrzx.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyrekzlb.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtyeyonqgi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtcpeuefhe.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtxtitdxzy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtxyshvrcu.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtxtyuzvip.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gthrgyezbw.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtxlbobtrl.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtkyutguje.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtosrxrhem.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtzxgnfonp.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtckopotbi.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gtvwijtsjw.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhqxhuud.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtgipflyxx.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtmkifngye.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtbomcokyy.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsfcsjlj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtbgvqnroc.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gttjamfuap.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtxgikorwr.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtoaiozqpv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtgvvnhqir.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtzzbghugk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtdcjnoiix.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtjvzeusde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtxfpllauh.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtyitpytvk.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtxnsvcexp.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gttwxkxeiv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtvzfsntsp.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtkpxiqphz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtdiddkwvy.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtarmymkpy.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtniacaouz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfvshkkul.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtowwjmqtm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfafjohof.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtrdhgayyz.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtbnlufmnn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtpnnhyetb.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtbfaovvjg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtfmgfsytp.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtfeaigrjg.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtwhhvjrhg.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfvcfnhz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuovmxvo.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtqdidgxvm.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtbxgtssye.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtrfpqqofk.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtufcbikcc.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbohnguj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtssqdszdz.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtjqxzkyny.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtqtfrbefy.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtzkmkxmxs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtfkcxqnrn.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtkryplgzs.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtnzzwerds.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsgkgqrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtzlhdkxrq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtlcujxqvp.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtbwuzenot.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gtmgcfaqeq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtnhruzitc.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtivzqalia.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtnqykcbqo.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtbobndgvf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtoyjnuiew.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtjihkgeeo.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtqpddfjvo.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtprlhldxx.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtgsykbmkt.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtedyadwte.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtueeqzxjz.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtnudrelyh.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtyejgmqfm.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtpgzkklss.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtlsilltpw.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtfqoqdahx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvplszucs.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtsulpkczp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtnsahtalt.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gttrixkfxs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtuubogpdm.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtwjftzxjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtrqlbjegq.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtwnoojodt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtknlaevzt.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gthiiswylr.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtbxqrkeci.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtshxotvlp.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtfxptyutl.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtcjrowlpv.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtnwnfdrap.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtoqhmjfsy.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtnlbvuekf.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtcjziblrz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtpajzjmyu.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtnoqxvalz.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtdvibktim.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtwrfosccv.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtufedeige.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtfyhyvhlm.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtidqryuuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtqgewesno.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpljjntmx.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtahbdvnpc.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtjmghzsvb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtykinpggk.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtrfeqhumo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtijzchlsy.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtbirletsr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtbmpaqwnx.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtsreeurnj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtcvygmehi.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtkabdpecs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtdeubncnt.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtkfbbqbxg.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtbvafsjxa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpgtfhld.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtjlpwscuh.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtrhrklmul.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtwohohfxy.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtqergylzu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtwzaezqnz.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtvefnysuc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtqamgxodi.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtsqlvhcsw.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtkhpuxoxe.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtqylrsqhx.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtmqkolacy.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtmavonwmh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtczzmredx.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtdcbvnpmb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtlqxetiih.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtvledhtuh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gttjgktlzs.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtgbjyjmrd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtayqhaqbl.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtwzhsuzgj.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtywedlarc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtnnmiwubm.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtdlycafxc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtjdnszqgr.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gthmtrlhea.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtkhroryxa.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtgblirruo.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtdbsurisz.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtdslurulw.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtjzcdxboq.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtfytfszqk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtkjiapwak.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtbvloanbi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gteshdovgu.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtjtgzdfkj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gtmsuxosfv.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtjxdtrtkt.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtqdyviyml.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtsyixlmax.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtbuzmjqts.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtaniohbgu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtucamnmxr.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gteqfwfdyc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtqldjvzfg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdcgamvwr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtriohoqwy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxeisqhqb.html


<!-- 参考信息 -->