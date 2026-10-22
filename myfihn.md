代发 wailian999

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtbggmhvyk.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtthihpvgk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtytmncwen.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gteyhvzaeu.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gterfkattw.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtqfzhyvjh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtjeduqety.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtretrefpz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtmexniyis.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gttquqkoeo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gthdjdxxft.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtncqucsmz.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtjuhuzcxa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtfigyatmx.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gthlfntzsb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gthxuxvrrj.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtzzvmqfzq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtnkgokdrk.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtycvxfmyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtwsxaqdol.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlzduspf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjvwqhrnc.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtuqgupzhw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtcbooohui.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gttjzqrkta.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtbbwalvus.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtsilagwqm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtfrkpxtog.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtwfmgqzoz.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtkgsadbyl.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gttdigxuck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtbkeppjfa.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtljjmnnmh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtvfmfxiuj.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtxbwmvrro.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtwwxmmvrd.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtqlrhsema.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtkwzfhsuy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtymafuofo.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtutrlffrk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbikmmuqi.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtnkgjrnuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtfnyvvttd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtflnegghj.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtegjgnfmj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqrntowgi.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtjyjmcupu.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtldbyiabx.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtglzgmdga.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtbvlhzkqy.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtxzonydot.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtgtxicceg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtjyjctiit.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtflathfcv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtbkyxvmnk.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtcqfvnhty.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtndeqahnb.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gthkvgiota.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtmkgzbyfu.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtwbjrwoel.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtrfsgcywy.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtcopfwlmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtomgftwkj.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtovosewqo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtjgvzligp.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtuefofver.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gtdtyzhrxl.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtutupuhch.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtbnhixlxp.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtwcueymav.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtpllnksgl.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtkekqjxha.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtafclcbgj.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtjggjqrfh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtgfalekmg.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtnnbcvyth.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtdymfdvpj.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtchabhflh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtjckjfbmh.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtcsbwciim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtvpqandor.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzymxkrp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtzuosrsjv.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtnricctai.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtdlqqwbfb.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gtokgocahq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtifutplsh.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtoxzhetzz.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtoozzukse.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtiabrxavx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtztvpfqrv.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtuqrafoor.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtlcpjrbwv.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtqdxvbhln.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtpuyiggpo.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gturuscqxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtqymrveac.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtbvbgrkfw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtkfgurjva.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtqvxrtywb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtdllzyocc.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtxjsbddfg.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtsqxtdvmu.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtiystxdcf.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtifniecqe.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtdujglykf.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtmpcbufhv.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtyqecukpg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtuwsptscd.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtluhxwlqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtaftzmqcc.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtmbdrrvff.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtthqzbrvt.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtmszumbyb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtbmqocmah.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtikolnrge.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtgpccihei.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtzvzcozfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtcsamjnbu.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtwagfjnlm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtzofzhhaq.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtmpwpianz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtpwccdudt.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtowoeohjt.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtvjqqugwq.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gthwctilgb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtfwzvgnyo.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfntsmoy.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtzkqdrxqd.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtvajignml.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtrxnsfnsx.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtdksamyiv.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtpwzkwmtr.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtmvuajkim.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtjgwogilk.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtvtervdab.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtabhxgaxq.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtogkhpojd.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtdpsxjndb.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtjgwnaeon.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtavkntnnl.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtjxheocob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtlfdqwqzf.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtwapgupon.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtnrdpxnec.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gttsuktyiv.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtwpkfivpj.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtibmxneey.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtsqnhyznl.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtscecriqt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtrohaitfe.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gttdmrlcev.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtzshngtxz.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtvibdldja.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtraxwxtqw.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtqjtgvgdu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gtbsaznrcu.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gttysdpbfv.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtrisjuzlg.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtoehpxgoc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtxvswokre.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtflvblmdf.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtdbzsxjsi.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtcqzgcwdl.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtipinhact.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtpebodxnb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtkfbwtnis.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtuagtalts.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gtvibbjeec.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtfchrflmq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gttwhsrtsz.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtktgtowne.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtmzbwsyoh.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtbphatnva.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtdqrhosqz.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtiaetflaw.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtbwsideve.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkiueemc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtechetjan.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gtbuxplgng.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gthsahywpr.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtsfctbovo.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtyalfntqq.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtltcmpcdh.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtiehhkcei.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtjxyummdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtfunmsuqe.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtymqjdiki.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtwmpyvlem.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtomlfmpom.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtbmqwducm.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtszezjmfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtlnqfsxkz.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtleikqdym.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtiwjbxldx.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtdffubejq.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtjicqwwgi.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtlwamvfox.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtomamzpdq.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtsucitvjt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtzetbvpda.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gtotkhnirw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtduphbimo.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtbzamxmwc.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gtwimqenwj.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtwvygzabe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtkzvocbyb.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtdjeyhauy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gtmcoirobc.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtiapojsxb.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtqvtqhlce.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjdssdiws.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtgujwlxdn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrkjmbjqt.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtmzeheycz.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtwwzowvod.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gthsdltkwz.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtponntxkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrvrvted.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtpjkrrcfg.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtlhxksqel.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtbllopdtn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtmvdfjvpc.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntfevztx.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtkvtuutic.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrdwnuad.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtnysdzdgd.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtkbyvkjak.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtyvklfoez.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtizbgjdpp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtbpsojfpn.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtdxwxgutn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtqazhpwzz.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtinpypstd.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtmopbpkxd.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtmpblkjim.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gtkubrwpry.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtewgdpvgr.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtqumheasw.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtiismkrga.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtmwykghew.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gtghwwwzat.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtjeseuvuw.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoumuhco.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtzckqjxlw.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtqbnyqnaa.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtvwinjtan.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtohixmudm.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtrggqhvei.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtvhwwywcj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtsnrgmpxw.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtmofgagea.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtyjqqyhmf.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtubtqncgc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgufhujr.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gteyhnexcm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtlvvimlqr.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtimerlosv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtlsyweiot.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtqvtrcdyh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtovowcbsc.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtxmhcewte.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtuacuupwf.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtbgdkqzkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gteogdtdrt.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtfnzsevpj.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtehgvsspe.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtpecqwpjx.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtkvbaxubh.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gthmlgoqou.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtphuakqsn.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gttlsvfjvp.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtyndcaeoj.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtavktjppc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtvnhkrqxn.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtebjwgnms.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtncsdcogv.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtzugesxvf.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtmpwhijyf.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gteesztwfb.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtpwitzqni.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtwowuhoyb.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxgbtqoz.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexqmixe.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gttparchli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtbyzvyzuu.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwckdsyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtfhofhiin.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtmissgyqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtpjewjphi.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtciniahjs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtttpbdtue.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtmixqqjth.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtxmyknkff.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtfctuwbpq.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gttpdwcegz.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtdclwukvi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gttvdwnlqs.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtcwrexivu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtxiuwoeqd.html


<!-- 参考信息 -->