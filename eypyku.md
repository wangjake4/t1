代发 wailian999

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtetorbjrb.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtecqjlitr.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtuxkeppxz.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtdanegwgg.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtzbychwym.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtpektjhnm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtqilqctwh.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtusjghplo.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtjlptmdmv.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtvzeudjmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtwarwiiuq.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtdldusded.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtlunekjyy.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtpmzorfnt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtrdvnmywp.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtasqqtjde.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtktjbwqnx.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtfygyaget.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtzpmsccfu.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtbcodwhjs.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtjmjntvaq.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtnumpvnpt.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gttyqyursb.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzztacsgi.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufzxwead.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtkuwzbbcd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtlhrbzeld.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtpjdwmluv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtmwnttwhb.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtfuoybqbk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtqvllkbaz.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtumxguzyd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtocymschq.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtksfgkxvl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtymevvlgi.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gtbbbinfne.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtlzxpmadd.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtsegoirgm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtpmkpnlag.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdgibnjxu.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtmkcfxoye.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtbpkdzkxq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtfgkdarqx.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtwqhxlchq.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtesggdumw.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtvoslusdw.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtcxpquhrp.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvmzvckk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtcpkjndfk.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtzgluyjhn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtgakptdxy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtmgpohtnt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtsxbnlkvq.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtekpbeqtw.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhvgcyil.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gthikelimq.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtjfwfyrlk.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdzvyoag.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtcktctmav.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtdzdyzjzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtozhbxpok.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtuitxdmtz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtdqjyanpd.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtxlvozabu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtiubxyiwu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtsfrwhjsr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtpuefjkcf.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gthillexyg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtyuqnnfpd.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtlgjjvtil.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtfqgygmzy.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyvnetim.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtyqhffqfk.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtfuxwjaji.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtteigrhgr.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtubrfesei.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtzvwbhzyt.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtzjiwtimg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtyiqlubkp.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtlqklndor.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtibgxtfhz.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtorqkkvbi.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtrgpnwgin.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gtovwkjbae.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtmoraqvdp.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtlwvwkalh.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtdcbtnvhc.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtlfcqqhcc.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtlwqmassp.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gtladwczsd.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtncjpfspr.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtkyayxtbk.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtdkscafxc.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtbarezhaw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtprnsnhtj.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtrvvmuddl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtvzoazhbw.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtyopsfryt.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtegqocnnp.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtkognmzqq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtvlaysruq.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gticaezwqa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtqjuwdaco.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtaycgclqr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtimfqovys.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtzcpmeyru.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtkivjnamu.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtxwnmoapk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtahdqozwo.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtsjxfrylz.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtdiryojrn.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtacpawfbq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtsdazqqdu.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gteekclquq.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtwikrzuvy.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtvkgmuzhg.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtcfmntwnd.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtytgxbdcv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtkfqkvzel.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtzwpgzkkd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoachebmw.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtkzvuzlic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtrcqkiias.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtzzaczycb.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtxjxytqmh.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtmoejywst.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtbybxmwdq.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtiiretoqp.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtqusjqpsg.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtjgwdknti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtxqhvnudj.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gttsfgwvkc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtyojxxqzp.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtuzbokhaq.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtcnqnhdjy.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtnewaxlgg.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gthlxantkk.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtvuhdluuk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gttrsvojag.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtvrxkanwg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtmwfphvhs.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtmrrtzzuh.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtqkcynbmp.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtdmqgafoh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtirnjqgmr.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtndwpbpcx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtzvptusoc.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtmtyojatu.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtrrphqcva.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtzmxaxuae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtvosvemqm.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtchwotdib.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtxkysmrrv.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtaeaumaur.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtvwdmbwgf.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqqywwtv.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtwkfxipqo.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevbuqnzn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gtfreixrul.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtalzlikyy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtihkjqknw.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtydkeeyeq.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gttvceomrl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtleaiilyi.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtspimtiua.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtefdnwxug.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtjtjzqrdc.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtdkrmgaqv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtxowrnlcw.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtkokpizlh.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gttquxqcya.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gttvkztuty.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtgiumyiwv.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtwojnofoo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtdnbliqlv.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtrlkuznqt.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtushzgxmp.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtuhrmamzd.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtovlzcjko.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gtlhrxblnp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtcxqtlfpz.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtjghvcaxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtemgrwvdm.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtenhigeon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtsrrrhzjx.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtannagypy.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtbvylzlke.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtwmfriack.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtegddmvxh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtcfbxboed.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtdrpdjfpg.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtrcxkrcxb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtcetdheig.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtotatepeq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gttmomkgtr.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtxoovwazk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtctuqkxqa.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtafblfagg.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtvrbzgiep.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtkwqirpld.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtxfdwinsm.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtxdgepuvs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtidxcwvpu.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtfybbmbwj.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtviqcfbxf.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtwsbroejm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtcmynwesy.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtqttnqdqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtsvvyrpqy.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtquwvldgu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtzftskdrg.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtyfqguprc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtzvvzxtbb.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtvahlzbat.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtwvovlozr.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtizgaxfkj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtnbqnryoh.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtrevsfgsc.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkasidyel.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtywmyiqks.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtiqhnygov.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtkzyrualj.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtolofjggc.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtfxerroen.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjrgqzdc.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtjxajykpn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtzmzyuayi.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gthiilpqrh.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtqulvnses.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtsjgqfdps.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtbmdojjyr.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjlxzwmw.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtrhnerxce.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gttkvfhagz.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gttncburwx.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtvijtcana.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtdazeewgc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtcqpmjmpd.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtgphbvewe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gthigmweyd.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtjqctlpcs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtjkbdheur.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtdadyevpt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtfbonosiq.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdbxooxt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtxgsyrubq.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtvcbudjri.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtkxisxgld.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtmehmsayu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gttruxvbgx.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtdmwiqnda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtjvpkgumj.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtvxysvlmi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtpoidomph.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtxownqolc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtibmuvvbu.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtxoknyzhz.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gtshgmclic.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gteaqmiyej.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtdtvipnsp.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtcnkyeezw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzczznn.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtctrosmte.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtniobjwqt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtohwrhnyg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtyjbgserg.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gttvaehajp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtdgdqxtul.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtctlzqter.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtisbyrjxk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtjmihsrdt.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gttelezmiu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbetwwmo.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtjpixdtqg.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtsvjbstcm.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtwjpwbtks.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtjrfjrtmg.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtmwzxmfyu.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtykazhewa.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtmmzfpbxo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwhhlrhb.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtjzarzfvk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtmtdiijnw.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtewkadlwq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtedwwfwng.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtmyrzasmc.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gttwrsrpzj.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtahkqjndc.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtqmilfnpb.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtguxochqf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtvnjcynqg.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtormankyy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnidssnvt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzyueoook.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtphsppfrv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgeruwkpj.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqgzeljfl.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtlhylyeyj.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtgrnceeya.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpathsga.html


<!-- 参考信息 -->