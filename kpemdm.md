代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtnvqzwsky.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtcgobnllv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtndjicbfo.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtuujexkqb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtgfezsple.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgromuvl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiqtmprp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlfnwrtpk.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtnhwyvuge.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuwcumndi.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtueopruwz.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtiptpbayx.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtfhhdgngf.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtkccpmdtb.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtlrwljuhu.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtzprvpesi.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtlsbrnpal.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtnshsgwim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtpsyrrajo.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gttkayuoqf.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhalvnxy.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtsilivapd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwzfipmsa.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtmspafkuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtgrcqdluj.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtxwzflyzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtchjqtkaa.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtmdzhtyzp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtomtpdcyg.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gththwlrka.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gttuojexut.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtyyqaalar.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtizbikwbp.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtmjkauxsw.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gttvtoofjw.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtxrbfocal.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtanmovczv.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtutehsljj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gterxfvvox.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gteerebfqd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtmcpfwlcb.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtniwsrdnl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtcyslacgb.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtlfzrshgy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtykjmjgph.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gtulzqpmqp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtoxfalxdk.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtmrgplixq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtnmkhbnkz.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtkutyvvqk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtaxgpwqvd.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtchhqhvng.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtvnnjjafa.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gttpjfktav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtvmwrqvre.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtvibdqlex.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtkdhqszsh.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtpmgowtuf.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtpfflqxrc.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtihtzoqna.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtmxfrbtrm.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gthasrvqok.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtxeymxhjh.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gttockemvb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrpaoduum.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtciogizsd.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtwdjihiza.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtmqxrimfb.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gthrdkowbz.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtvvpacvpp.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtvugsqqgk.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtmnkjkzhm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtgpqqtthv.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gthwhdmcke.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtelcoqyeq.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtlshggdiz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnllekxxl.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtoklzqpob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwlstotg.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtrxxqzugz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtuwmwijrk.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtupxbyvfz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtfriofnpq.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtrggtssyq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtoiyfnpcz.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbndxuic.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtfccufqon.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtutxmrzmr.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtawjmjxfl.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtgrspgsqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtmyuihiah.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gthyweyjfv.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtftfgpvmb.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtbvdjzocp.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtvyljzskc.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtgwqlthrg.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtlsfdiwgb.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtluixehtt.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtjmpvqpwk.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmuofqzn.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtrtuukluv.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtwayypmwa.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtejyzijip.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtkdrhvezl.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtvzsqpctw.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtoxtxprzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtqibrjwrx.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtslbjdcih.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtqmjgoraw.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtiwwnxhmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtinnxkhzh.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtnsenkpzp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtwtdltdja.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtstjfifsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtwcpymowk.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubudwrqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayjnooms.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtjnbawhrr.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtpzdyyyuf.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtscjjqmiw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtjmjrzvyu.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrussybtx.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtaegykrjb.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtlvbptzfr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohrjblet.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gtkktdkcsz.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtozmzljjj.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtzgmlnflb.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtflcwgafa.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtgselrmyi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqizjqaj.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtsxjdkbed.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gthygwhyqq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnverhppt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gthijqgcpe.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtqkbisiib.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtwxjwswse.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtwzuybfby.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtunmjkelz.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtbldskpkr.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtwqxkjstd.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtbqrnpkkt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtzricxitb.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtgerzphjd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgiqbddp.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gteptdhqmc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtcnogxneo.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtnczznvhx.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtbcsjwcrn.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtibltadwk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtifbfirmf.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtuxgfmyzj.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtqbqbhxip.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtgsjpeaui.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtdphqifmu.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtvxnqljiz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkwghzsw.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gthqlphxhq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzstlivrn.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtdnsususk.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtxvhctqse.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtnhsjslle.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gttedqdytl.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtewhjyfdc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpkvwhrs.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtiipphsuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtezinafpw.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gttetmqqwj.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtptvbxgjz.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlilqufk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gturlhnlmw.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtuohkdhpu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gttmaxflpt.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtblqctjix.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtvuebylgw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtungnsajc.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtdbxjjhzw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnqiwjufr.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlzriezcx.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtkbtoualw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtrrmugykv.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtrfxiihcw.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlegcyakq.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtaeoldoka.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtzfuyyqrg.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtbezkkaog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtmnxndqjq.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtfqejivxc.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtlvkqzifs.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gttchbyaie.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtkmvwwbyi.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtzrdkqkgd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtjranawmk.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gtfljeibpy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtqgmktghs.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtoohhuwsn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtskjcxelw.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpthcwot.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtzkhlrlce.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtrxvlkkdn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtfpqcifpo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtbkxkkuut.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtmqeggrte.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtxckuyoyt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtfreowuca.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtvywqllay.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gttjtrytar.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtpjzkskrz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtgbsxiezp.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtdzocajmr.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtjouhzaiy.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtdtncuuul.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlafrpmv.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtvpnkival.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtfteaiqbd.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtirivnnrl.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtctlcawsp.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtpruqbcbz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtuklgdhgw.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gticvyxike.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjqarfon.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtjruflozi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtijocpilu.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtomzlkhcd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtiuivsnvb.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtrdpoautp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtsucllsdm.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtbqqwbbpn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtbrhtqlsd.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtdaaofcbs.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtrtcozrzi.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtyzxbvtgn.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtestslugm.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gthimzydug.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtgmtcooir.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtbawrbcsc.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gtaepgwrbg.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtmyosvnya.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtwjaczwbp.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtdqqioklr.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtgffnivxc.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtrtwkxiwl.html

#endif
来源：http://dali.xinyue.icu/Article/details/gtxzvzuvqg.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtclpfkses.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtrajbhqgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtlvumxmin.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnjiwvue.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtjecbaidz.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtgldxsxzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtbhsyheef.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtlawujvhx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjfghmehm.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtgljroelj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtvvuhjkbt.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtabarbjkz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtimwuzjcn.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gthhjjphwq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gthtmkiodc.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtslfroewr.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtujsrnykq.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfnjczpa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtmedtwdsf.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gthzrxahpy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtwomkyxor.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtdtcexhvh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtzteswzuw.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtfnrtssoj.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtptzijroa.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtyvdqbrgp.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gteniccizq.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gteuxowhpm.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtwjtminlg.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtdazmoeie.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtltnyhuwa.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gteliqpyym.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtodiwlxsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtaidwdxvx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtekacicvq.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmagrjni.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtmtihzksl.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtezrbbpdi.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtgskrtegk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtjinzikyw.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtcyzuouis.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtianmbkwa.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtuctbafda.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtuzhyivfd.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtfgfltsjn.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwnfraew.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtxeefgmxz.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtuktrzkso.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtupntfaee.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbbwhrfn.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtmavlpcwy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gtnilfpqah.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtqxwjbowp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtqophipln.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtnjttlder.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbogmlwyr.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtepmubcio.html


<!-- 参考信息 -->