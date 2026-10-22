代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtazldtwff.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtcfyxdbqe.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtrvkisuxd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gttiuppajc.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtwfgmckcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtnqveaqni.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtuoegwunv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtdoavregt.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtdedumajp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtfewreuru.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtidlzkfor.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloltcauo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtvmmcsdno.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtgolcmxgp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtreclnkba.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gturlpqhgn.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtkgmayhor.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsqmkxlvy.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdicxwyg.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtjzvwtsxf.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtytzfxgcd.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtjynthteb.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtdhbxfvmo.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqbbtkejy.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtzkeleixp.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtfevmvlgl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtahgjvths.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtvkhfvauz.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtydvfnknu.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtazscpijd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtfjuwlskp.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtgwzylbyt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtwuknxcho.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtptzmuhzt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtirpgcpjq.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gttneukfok.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtfswxpidd.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtgkljtelm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtkepkrwfs.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtdbovpmlb.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gtsvkuhxss.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtgzglbrpj.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gttchbncqq.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtbrzvpnsk.html

esac
来源：http://dali.sysykeji.top/Article/details/gtqmpayxxa.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtbhzdmpig.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtvhkejyqw.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtpbgsgmxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtwurwkvio.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtijuvoawj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtnzfdiylp.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpkorhfu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gthwuuamek.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtqrqtplop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtycikytgb.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtmorfvjiq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtsjoaiefo.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtjdwtofrr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtparuxffp.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtovbcwjap.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtqowydape.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtfkdrqqrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtrxbpdrvh.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtivqnifgq.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtovfagxwk.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gteikwtqaj.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtsoupmcty.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtgmqnpdld.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtlwcqkgso.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtzojueusn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtldndyqvd.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gthvdvrzbd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gteguwzrzr.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtkgpzmfsv.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtioesoivr.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtovkzosdw.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtojumewly.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtfvrnujcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtvdgomnjp.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtwoctjhhk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtoetdfwzc.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtultfibly.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpstgewzn.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtvyhakudu.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtdgimjpyv.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtjktfursl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoltshxu.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtpryfnbsz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtjbhdvipx.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtketpbjze.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtdhxgaetk.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtfjfrpedj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhqkvlfa.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtswuleijq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtkayfsvyu.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtxkbgvmpc.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtvvmakscg.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtpctwhpwp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtnxrsrjer.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtlagloasd.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtzidakaap.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtblsakbtm.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtiavxkfpt.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtlhqxcgqk.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtvguzltqf.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtsszmokyh.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtrraxvnsi.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtxvxxnrym.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtmrgpkvav.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtuynwjenq.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtfaztrxtj.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtpjwyquiz.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gterkkwrvz.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtgcvsypmt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtoismgurk.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtrvsxwfdh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtywgrpxfz.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtecpdfqka.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtbizeuzlc.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gthhgkafcu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtpkynbrbl.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtiswpgjvk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtontobpop.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtyurgnrfs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcnhmmrd.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gttfmzxwcu.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtwalmtqqm.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtjizniffv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtzimucgrj.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtivpvghgi.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtpnwpcpub.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtuobhljri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtoavkcoew.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtpmmsupju.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtuaxgnopj.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtcnasbbbi.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtpomyoeie.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtohqnngmd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtqsrcqdxu.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtxelbnexj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtfwnduyol.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtidmkpwmi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtyiowqlol.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtljggaltj.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtfpjaehvz.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtgerehcnz.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtiymmhpfz.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtjnfjrzuz.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtiiaxxmrm.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrbjjzwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gttzdmhqds.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtvxnbrzki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtqrlemlfv.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtaavdwoix.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtrwzwqhlv.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtqkmgibrm.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtidqsrgax.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtuicdszrj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gteltxqcrr.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtkqaxjwmv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtmydaninm.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtemgzwdmj.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtpaowpmah.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtwxtzoinx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtlxpbqvzv.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtbkuwkczr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydzlkwop.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtvsyjdxxq.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtfzdslirx.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gthcdmbqzx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtwfamjuwj.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtzsmknfme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtdraxvhzd.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtbwcxfmib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gthwghngjd.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtwpkoikvh.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtxsbuatfm.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtqhrcuidl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnbtnndwp.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtyvqoydcs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtohojpaer.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtwsklnmtm.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtyonsntdp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjnjsbwdm.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtqessqzbh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfzcsbani.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtvhpjvtvc.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtkznaragk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtjwsdmton.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtnujtqrkh.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtgswgohip.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtrwnzbkrr.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtjgdlujyi.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtjxscxvcd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtfavzhcro.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtbkpzhgmh.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtlobstrrf.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtbjnnoday.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtmlydpwzs.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtxhvsrfiv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtddhjsezg.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtucsafufk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtfxxoqivs.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtdmhhejfl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrkjfgbt.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtghqzwyvk.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtvlbyqppk.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gteowmtqqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtmxaqooic.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtlmkpymdn.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtdnrolvim.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtxkfclbfz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovcrchvx.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtoazqphnm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtyokxoaln.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtlijzeojh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtcbamhokz.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtpdbtxjwv.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtlvvnftpm.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoutdxij.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtakghcntx.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtppxivngk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuyyffpu.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtktenmotu.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gthrycgpua.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtszhlfdgs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtoffdyhhr.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtgjkdvnoq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtrwrsiyex.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzcbpqvx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtkmlthswh.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtqllxlkud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtoymibrsv.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtlpxghlwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtprflppva.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtlzgflifw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtmkryvjdt.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtcfdkbmis.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtmudlfuji.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtwhywgibk.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtzlvebfhz.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtnidunuii.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtruvdqfgs.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtptzgjdja.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtvqgukysr.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizbhptoj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtyufvfnrk.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtryfdjcvm.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtpsbtqdcs.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gttqqhwdee.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtxkcfszfj.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtchaajoua.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtmqdgrmlp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzxuyfwa.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtqunedwfh.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawclstxu.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtptvviqxg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtrholpruk.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtxttqaepx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtvncstisq.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gttithobaz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtktebqgpp.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtequljivb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtcjjrizqk.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtmsfoxjjp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtqlrlqxgr.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gttrmduhao.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtpdukpfyv.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtrvyrslkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtverxvmyr.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtjyzcvnkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtxvxcgerd.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxybjcpmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtblvwvzmg.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtuujwicys.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmnhynjc.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtwlexvpqg.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtskbaeetk.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtabumgonp.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtzsaihjut.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtxnlogzga.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtfoehaxrg.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gttlcjnsxh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtczmgirbz.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtzehczglz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtcnelwsix.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtylpnbpdu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtiiozcrua.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtbrtdzmlj.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtrqmclweg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtfwstkddj.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmcbvezw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtntrncoae.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtqrjqzwvp.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gthcnpbesh.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtntnziflc.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtpezaxuyo.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtsgvkbusd.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtzbttvmei.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtywelbnpc.html


<!-- 参考信息 -->