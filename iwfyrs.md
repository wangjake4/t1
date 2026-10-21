代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtekrearch.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtamemtapq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtisibmxmd.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtiufudqzk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtegthqzgn.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtmyuwoglw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtqgplpnpr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmklddusy.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtqrnzcodo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxcvzkdu.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gtlbzluizz.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtkaqtlnbe.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtosjiqreq.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtjslqoceg.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtgpiowijm.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtngspbihq.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtxfcvvbtu.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtjnbpnnpx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtqjjwsruy.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtnrrfgbnh.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtcztvgpyj.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtevxcbcik.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gttackgspz.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtqqtpblth.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtpntcruxa.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtqkjyenqm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtpiwdmtyl.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtgsddlyas.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtjbpfbypq.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtnldpyckn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtgidxwbei.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtbnnsyzlu.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtxwrzpjrw.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtrxsmzvkj.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtwixzigfj.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtgafjqawr.html

esac
来源：http://dali.sxryk.cn/Article/details/gtzvridvpg.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmwuxzhzt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtrmaombzi.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gttccadfer.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpqktqzjp.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtzeogxqxc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtttmtrnpq.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtmfjdfnzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtepodvcya.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gthxirjjhx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtbenoilpl.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtsbzddteo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulrtkiqe.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtnmhnknzi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmzueghff.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtvzgpdhgi.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtzdqkplun.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtajnldgkm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtqagavppy.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtgpkioiih.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtrghacebb.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtaocjgqig.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtvwvrcbhb.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtyvtqtgvn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxuvefgdq.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtzncsghyt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gttggmskxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtncswfeve.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhjhktbd.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtbrqgjgwp.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtewjzkqop.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtmyjnssoi.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtgswxdqtn.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmusjccr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gttuagiyoj.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtoxcgdcbn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtdmyjsywz.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtxiojpdup.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtnmirutxb.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gthwdftggy.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtvggftaig.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gtjqwmzxkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtrvfpwtfq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtengslojp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gttdypiwxl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtihggoglt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtzssvqanl.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtygxgtmiy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtufmywkqd.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtnguzwhxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtxnmhkhtx.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtbxuuhjgs.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtxqgghlid.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtvmppgghz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvhvokcl.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtmjunulqd.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtvolgnrrx.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gttgpqvnux.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtlzcorvcm.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtwouuelok.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtlvvcogwz.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtzxvmzkny.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtleritrwy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtdsietgmr.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtmqymbgks.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gtibclixoy.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtguttipuw.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtmiopenqi.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtvrxjjskn.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtireayqgc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtstvkncoi.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtibtxpgnu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtusawcxuy.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtxsaisgsr.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtwfibcomc.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtwyfiwhxa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtejuydwlo.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtjwijukqa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtiqmxllhd.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gttiitysop.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtfwoysvkn.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtuogltqyu.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtdrdwabjc.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtohpfxkps.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtlukcxtlz.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtlwzhjfxv.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdcjfieuj.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtdcjtiqxe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtmpksknbv.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtliyvavzv.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtyrlfxwra.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtnsxyzsvg.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gthpnlxgfo.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtamnrmcmv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtscevnzhv.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtfxiimxrj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtcqjiazdc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapauppxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtaajwtuli.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtvjerphfd.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtwilswiub.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtmokwiaou.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtyqnmhxkz.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtxtwtdoia.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtdkmlyfvx.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtevdglmyx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnybbhoa.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtszvkgmam.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtwoyynsya.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtxfvpcrtt.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtfbasctbw.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtaeyuoyes.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtwdpjmjao.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtjxtbdjnd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtejqakgjz.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtapjesvzh.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gtquujqgeo.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtesjmolzx.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtvapanppw.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtxgjxxcuw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtthvaibju.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtaljpseyy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtskaogtfu.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtvftmpypj.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtkrogivua.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtbrmipteo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtgwyyhkok.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtlyfjzekm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtgabeianw.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtvpfezhht.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtxefkuqmu.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtpfphncia.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtpsczzbtc.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtkxsfypfq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtmzhdjsio.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtgeqzgssm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtglecffku.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gtvnibnnqf.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtiqvhkyit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoqrzasef.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtkaoqnasg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbllsjdmf.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtbhsanrlq.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtddjelhsj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtukmxsxig.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtkzqzefaa.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmkbuajx.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtwmqmjflr.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtovujzvdi.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtpywtpftz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtluheogpd.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtvmflqicn.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtdbyzzqkc.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtpxqenzrl.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtqbgayhdr.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtinypvmhy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtovwyytpg.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtftonjlam.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gttzdyefdu.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtpiownpis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtsxxllalr.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtvldjjsfa.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtzunxjebg.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gttgssafzc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gthzacnakr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtqbtwytzb.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gttrajmzfa.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtdvtkutkv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtiqkmsqso.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtvshcuaxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtaxxwhxub.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuiksthd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gttyppgdhc.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtddmeiscw.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtglvphslj.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtheibcllg.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtukmbifvr.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtdgibotmm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtuycozgyb.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtqxrsfxqh.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtkvgmhlob.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gttsqtpaql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtqpsamzip.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtslfnhnsy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtsslxnyge.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtrxsovpoh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtazypwvfx.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqmumhwp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtibnkpjjz.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtffbgliql.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtjjxcbgxf.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtcnkosajb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtiupevmyi.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtkebjsccg.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtdlsukbqo.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtyxzitwmb.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtjbsberpr.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtfnldbgnf.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtysxnodot.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtlxylylvr.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtbfgkbnvd.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkwhwopu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtydwnyqfs.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtvpupheqg.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtkhyyeqmx.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtsutjtveo.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtaxeujjku.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtqlwlrbhg.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhxbcrsf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtabtlnmll.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtxyglxchf.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtzxqmafwb.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtjalcvkns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gteabobbch.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtwvjqoiuq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gthbwrlsvi.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtjfyxletv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtkxlzqxly.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtarlwqfav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfzotipn.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtrwbymqbt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtqbdchwka.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gttpblqfmh.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtwyrjluwd.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtpwwasgor.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gteeakhxth.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtqdywgyva.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtqjetvxbk.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfiugkek.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gthlnzxjwb.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtavyextwx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtklabyqcf.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtnrfbdlqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtigfevtne.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtzpjhgcgs.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtmcjnqmko.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtwlgfnqxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtikfpvfxp.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtdgzwuyjq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtyodujqgu.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtmmafgwet.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtgppwsmwt.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvnqisbv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtgxpzrbzt.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtpxpqxpyu.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtncznczbs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtujgreett.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtfrwtarks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtvfuqueju.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtbwthpfim.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtifjoylqq.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtidqdvdua.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtsjoairze.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtccvlrbju.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtxzfarlqw.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtblsyqeff.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtrslixmbg.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtmufsprcw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtwfdzspsf.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gthetvhkmr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtiilmuryq.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtoceqzipl.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtapqdssys.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtuhipvsti.html


<!-- 参考信息 -->