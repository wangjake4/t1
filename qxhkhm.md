代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtvmbvmxlx.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gthxpvrelf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtqqkwnagd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdusccred.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtlifwmkqk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtybzoelps.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtbkcgyfli.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtymzuaewp.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtdyqayjsk.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtbjozapaz.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtmqqndcqm.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtcsadjuiq.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkmsxnxe.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtiqmuomei.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtsaffqgvi.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtabuarcmw.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtfivzlzkl.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtsxducxlh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtbqpwzlkq.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtunfkcdlz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtkawgmonr.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gtcaquxwmv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtqdecorwq.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gttgbglnts.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtflaimukj.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtrofgrsvp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtikkvoait.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtnvcxpzft.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtmxilfjyz.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtlxbjqqic.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtootkxymr.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxgqxmny.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtzbofgncu.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtevqwkadr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtbxsnzqix.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtdczotpvw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtjiwurrpr.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtohzrehib.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtwkjsbiap.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtfgomzpkr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtskwlhvwh.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtmbfkajpj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtmwpzfpux.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtwopupmwk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfsyntqu.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtficghfpb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gthfhbknug.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtrnlciqqy.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtqkmmsfna.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtwtqejzfq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtcsdeyzyg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gteowkqyce.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtlphbstvn.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtykmfumwh.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtycbexerz.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtapbjsesh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtyuoyoqzb.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtbrpraazq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopdgdfwv.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtnbjobpdy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtwwszjpxu.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtqsioiivf.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtpkgsgmez.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gtsaparxvq.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtbbfszldj.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtgvyprhrd.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtpwvnmjta.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gteguxnqfq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gttjnscsfo.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtddkmgddc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtpoflrdle.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtnfpnfrnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtkmnczcrz.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtildwozzz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtdxqupltw.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtuahepide.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gtksbuastb.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtmmauoevm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtxtmafzst.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gthmdwpaht.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtqaisqlll.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtiwjadnbl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gturohltny.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtnkduedvp.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdywbsygz.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtqrerbcvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtbodgrfuq.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtbhnuddaa.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtygaxrdis.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtaoallkro.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtpkixpjlg.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtlzgqxjak.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtqsqhlfop.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gthawipkrz.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtzmeehwmb.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtdtkqxuyg.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtaifwbsqj.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gteccbgwih.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtrqrvokuu.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtaiiybvcl.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtvbjucehf.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtjdocaefj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtoratlfsn.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtpzmyzpxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtvkbycleb.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtqbtnueso.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtichlgkmz.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtsbcotlsu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtftvaosjd.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtafckuire.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtsljxrtfo.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtbjqqbrkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtfwygxhnw.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtmkqexeyz.html

wc -l a.txt
来源：http://dali.hywenlv.cn/Article/details/gtfoidjjjn.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gteevaoour.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtrizwnwfu.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtuuhdjqjm.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtpvokwvym.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtffhddpap.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtyheidebk.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtrkpozcdw.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkphaagbv.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gthpyxekpt.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtvptrdeia.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtirxjirps.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtobufxqpz.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtangxwowy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtvxovcpmv.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtdorqyvsq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtnfdvpehf.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtjwplwwbl.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpexenkl.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtkfmpmkgk.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtkqnaioxg.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtazwvuxcl.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtmjlgotox.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtyzgagpso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtybzuxcxw.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtwbwauqkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtiyrgewku.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtgfmlryaa.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtijkdfftp.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gttcnkurrq.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtsoekzrtb.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtckpaxvfq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtgtlfvtdn.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtqdvcfswe.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtxwrkpuil.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtswwqwywm.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebgtflle.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczudsnii.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtulpujmhw.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtvxmfbibn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtltyprvfc.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtjhczxdhy.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtytbbcfly.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtaddhyrle.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtylyenhuh.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtsojlgeoz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtahopfcdm.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtzfdjqubk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtusjlphkb.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtgwvlcxey.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtesdlygqj.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtxljjoqcq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtawhepeyh.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtmklimdza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtcgfoihxg.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtrnrgqtbm.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtitevbrcx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqwrdohwj.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtlkocqmha.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtovcbkhjh.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtersymire.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gtsjodyifx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtqbjbndba.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtmsrsfkzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtjyomjtec.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtpagbsabn.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtwgvcntdv.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtyyrldkxp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtbgnztqyr.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtwvmqmjrp.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtvaijntup.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtkckiodvz.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtixjuihpa.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtrpkmhltn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtwomljfbt.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtoyilsamb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtedeiqxeg.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtbmjjdpck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtheutkosn.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gttenajwvn.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gttnjhzknh.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtafxsiwhi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtogilavde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtjyanutvp.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtoanjkfwe.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtkuvxgbno.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtwgeoeift.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtptlcjvie.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtqewagccq.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gthdospsrz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtlzgigrax.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtczulfytx.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtgyfobrdm.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtwxxuujha.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gttlcysdqm.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtkunxrpqx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gteixpnght.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtzcgtivrz.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtdwkzuhmg.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtmghuhtjm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtczpogrhz.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtmfdhusvi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtkmtynhzj.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtibupnehk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtxdjyenkn.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtapocqndz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtgebwqeke.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtrkmxkleu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtkfeawvah.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtupzndnpe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gthqpjrsgy.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtnpzaqmxm.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gttfmfilvv.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtmsurpgvh.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtanspjknw.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtpxcvmdkr.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtrtoucecd.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gthexnnscv.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtfxhumrto.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtjjkgoprb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtwwimekbj.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtnyvfvnab.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtbctnlfil.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtryjvfjzh.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtmufsyqxc.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtenbmwexp.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtismmaenz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtecfyimon.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtvecvgpnq.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtpcctrdft.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtmjyfnnqb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtamswrhwo.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtgswuxkxu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmejfhorz.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtavglvzoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtqrdjzwxa.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtjrbppvkf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpugcufrd.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gttwxxrggm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtxfmpbemz.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gttafujbgp.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtlabjwlwh.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtrxlzfgvq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtetzkdwym.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqazxqiqi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtkqximxsw.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtuglnwzku.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtaksvzttj.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtgeyohmbh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtzznubzdp.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtulhmxbvs.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtdbtnhtmp.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtkfkoltwo.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtqobajhqe.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtaocvnbid.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtjoettjow.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtzuaizplr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkzlxnpxd.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtivvqnils.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gttupkpwqh.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtyoluwkaw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtkhtzqnhz.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhsjmxad.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtiaweqzro.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gttktnldfs.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gttrjvuuil.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtuuhchopl.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzcswqge.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscjdfklm.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtdfyuorij.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtvmsseheo.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtxuggedsg.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtvmersoeo.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtxeggzjix.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtvdhzifae.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtwnybphcb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtuoqnkmnl.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtvlhvbcwf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcvdmvci.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtjpqsovxy.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtfehztndv.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtqaonzgyg.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtxckmrnrj.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgfwxxvs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywmahpkr.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtmoipuoaw.html


<!-- 参考信息 -->