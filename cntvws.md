代发 wailian999

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtwfiuzojb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvmnfysdj.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtjrctxijc.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gthrjvuyrf.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtltlvpyxf.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtyrgjogmn.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gtxtqwlosc.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtwjuivlnm.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gttbyqmtus.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtbkutxxhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtgvpczhvx.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykqcztwp.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvuqlakt.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtmamomofq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtqcxcilws.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtizqgnwjl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtxcbyhjju.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtkdwuapua.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtkhtosddp.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtaykahiec.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtbawehbjw.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gttsvlpwru.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtuymsnrtm.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtwirjqest.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtqqomavka.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtxbazhtpi.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gtjibpekjp.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtidqeiprp.html

esac
来源：http://dali.yangfankeji.com/Article/details/gttzviqolg.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtotebaivc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmndrdsk.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtojhsuxqq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtwwycoute.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtnzmnhtgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtkotuvlpu.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtuofemgvt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtcllmlkxb.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtaddbeypb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gteweitvzh.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtymddpumq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtstwudzbt.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtndlkxgay.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtsydbcfhb.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtdjlwimjh.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtthzgrosl.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtweymseyq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtnllluvef.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtfvfirqxf.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtvpxxzzcx.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gttwggnpph.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtabtytpwq.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtnzfsuqao.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtunbmzddb.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtucwtbahb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtcvwxqhwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtfiyxiegq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtdyfnrovf.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtuzbladqt.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtptikmfjy.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtqmsudyoe.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtqvqwbjmp.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtoskbevnz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtufoirirj.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtlvemvbqh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtydxfuacu.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtwidqtned.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtplraslwa.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gttflookhv.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gturnjvdqp.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gthustxmbb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugpgesgv.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtcdjyqnvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gttkuhvvxa.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gturmdnuam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtuevslvls.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gthdymcnts.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtfrrtiriz.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtiwajagwm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtyyiytcjf.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtxfhiiqzr.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtppivqang.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtymwoayrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtpwyueynp.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtuyqmihjh.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtwpkjuwhy.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtumxzbgyc.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtilildpzy.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnoabngg.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtawjlskqj.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfljmdjim.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtqxabmuyk.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtcuadvlri.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtzuxpmwlm.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtuzthukfz.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtyycnymth.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gthzroasxa.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtcgpfuaiw.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtrgkzsrqj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtpztgvzke.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtmojiufqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtgfzyxxii.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gttareldqh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtmtzljwhb.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtxoxjydgd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtlegpheoq.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gthfmxhovt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgdlkaxzo.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtifiyhqio.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtukrytjnn.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtrkuyxecr.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtunubztvj.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtlvcbbwta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpftkrkg.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgowmhild.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtmbxvcglm.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtnydxehbg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtoprkrypl.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtkfsznoyw.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtksywxdnv.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtfqgpjhdr.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtfvhummuw.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjzaofqh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtvznkatqb.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojibgjqg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtdtdgekxe.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtvkojlhfq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtaclrnimv.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtbamndigd.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtxuoywksv.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtukutzavs.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtcboichnh.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtqqlrzkkb.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtuarvjrnp.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtogiqagms.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwgoxoqd.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtgozwagvt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtwehrjxzm.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtnrbleaig.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtfkxviawl.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtwccfjlvg.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtuhyopjhi.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtkpvtworw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtydejooeh.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtbpxpdhnn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtoedzuqvu.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtwilxotpb.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtikliezlq.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtsghzbhko.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtrhhgvjkp.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtzmjgfsgw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtfhgjjbpb.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtykwtativ.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gthgcqzusv.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtkrzcxydy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtibgvjjio.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtdbgrjpqs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtyamehasy.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtukkijptp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnucmnlx.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtwbcyxrlc.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtcthkfqyo.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnkmrrla.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gteowfhpsl.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtbzdmcyal.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gterjcctaa.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtxryqqxvx.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gttmmkrvqy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdkkleyam.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtmrtdmgic.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpdzkrlo.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtvqvgpmwr.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtzikpjkny.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gttnpqutlw.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtbotxsiih.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtpqprixnd.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtorxpzakf.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtqdjcnpof.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtudcnitll.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtpyyhapkw.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtfabzfotp.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmzzbecwi.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtcsptiklw.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtuwsxyuxh.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtadgczknp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtimewgoik.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtoyzpcdem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzufnptuf.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtpbfekgbp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtyxskyxxd.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtlgboywos.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtruquxfdy.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gttjuqyuif.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtyjcqhtwq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtymkcuhst.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtwktrfqby.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmgzcueah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtwhvuzkjr.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtbjvrwvdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtobkmzsax.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gttunrofeb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtapnshakl.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtemytkfuk.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtpanstera.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtomkgnmcv.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtepmmqfgl.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtrwjwijuk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtpzpozqxf.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gttxmccxng.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gttooytnbq.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtvuymskaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtsxuuyxen.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtztrekdza.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtkahjeaoy.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gthefnvklr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtowfkfrhk.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtczqhkggj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtorplqwem.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtdderqqal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtbovrjrmu.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtkehwyjae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtisygwdwe.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtmxbhwxed.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtipmyeiem.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtghbfqocm.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtzduangmv.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtlhgpcosa.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyztqlai.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtjrikhuws.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtuxiavgxj.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gtmhinzeit.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtevurwcwt.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtntjdzxzx.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtiunqwnll.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtdufellsn.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtvbmhdfjq.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtrbrqxogs.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtjuxjcxrv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtfssgjmcn.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gtdjxczgcp.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gtqduyskwk.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtgndokjzl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtijawxulc.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtchclbwiv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtzzzdouua.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtcrtolfqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtnxmeiodv.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtdlvdfyuy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtjdwgfmdo.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtuldosgha.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtddzdgqrn.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gteusmcxxj.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtxlsiqfoz.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtihmxfbhb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtluomepoz.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtpnirwsam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtiwbumyzi.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtszkvanzx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtvobvubcw.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtknmqlhum.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpnevwxj.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtnysrjcaj.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtctuljtub.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtqluhaime.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtiagozaai.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtzzwdsxii.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gttjnfwsxb.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtlmghcdms.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtfvlsqflc.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gttlreukdf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtiwazerye.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtajbpewos.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtiglltwpv.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtrvrbxhcb.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtxandqjtt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtjwwuthwi.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtzybgeaur.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtgtbccimj.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtxfmzsicj.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gteywuhvmu.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtwpdwpklp.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtdcvidkrs.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsaudkrz.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gtcqeyvffx.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtgpuiioqy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtkyuezcjm.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtfmiegokf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtivmehcvn.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtfhdqsctk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtgutlvjca.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtkzxsnied.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtulutpqkn.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtfhktxzvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtnsysigku.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtiflgayum.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtjxotnbtb.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtpoqvjfmm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtavfcprvk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkphkcdov.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtfaarvehw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqibobjax.html


<!-- 参考信息 -->