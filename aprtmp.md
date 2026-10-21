代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtbclhhuzx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtuwzvyekz.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gtfouhvphk.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtktcvqkfp.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtofyhijfz.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtkivmntwk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtomkskfww.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtjysctgbp.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtgaksckce.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtzvgeoonx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtzcrrwgsz.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtrimoqopw.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqawrdt.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtdomkykas.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gturtorfvr.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtneikljec.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtpprsmboa.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gttsypwnqt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtfbqjzkdz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtanevyhsz.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gtezrllutj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtnmcnecaw.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gtpycnxnqa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtebnestpn.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtozybuugs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtmigcmykr.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtekcnwvev.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtznbbvbul.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtocucvqfv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsmmlsko.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtsjvxqobf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtyxetouba.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gtrwhdztva.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpafkywjk.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtkduqgtyb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtymvaptll.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtilnilnlx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gthfkdnhdi.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtipnpffli.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtxwpivqtj.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtektuvrul.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtfrbzouql.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtteglptow.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtmczbrgom.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtaymdcgms.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtuhukndzm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtcdkmjuzg.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtccpazrfs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gttxnfstgc.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtuzpkqxrz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtvqozykwc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtshavuljz.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtitfcdvtc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmebggret.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gturxcaghf.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gttlldzfeu.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtnfauniis.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtkxchvres.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtfrezesll.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gteesdgdxt.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtubprremj.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gthvjfzfed.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtrnkmvohv.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gticljxlzt.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtcvvburlr.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtedpquhbu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtyikqljmu.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtfdijcvsk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtnagvdzss.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslrrpwbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtwuziitfe.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtyjrqgmos.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtdssyeekz.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtkuvsrphv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtqfylfjwq.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtvgykjlmc.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtogyajjuu.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtfgevcrlw.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtvhasokpy.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwpknepz.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtcwwrdnvz.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtbxwqvldo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtwowahwxy.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtxatltrvf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtgpeknyke.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtmijfsjkm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtbosfblfo.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtluyulrge.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtzzxhnxgp.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtqutdqlef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtsretyxur.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtmkbzzrwj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtzfnkbysx.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtkmovkhtd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtcjoigjss.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtthdxlvle.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gttrfhttrl.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtwkthjdkx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtbjjmcdyt.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtmbivdard.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gthxmrzxxe.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtpomravjd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtrfvmvfgw.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtdadynfoe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtycckywft.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtdaucgoem.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtvjbhnshz.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gthvnhhnvs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtefszdjio.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtqfifhukj.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtkddzfscg.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtcxdfluuh.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtlmijoayp.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtfvacvfxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtnvkbaenf.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtlxslnvwr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtjylxmgfb.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtskpannas.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtuzlkxejd.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gtveltifso.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtcgzxwqrd.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtlzvghzht.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvnrzrzsg.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtdhvsxewf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtjvghdzgc.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtwubpvrbz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtiwdviqxd.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtfihxjqzn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtatzleume.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtpcxfbclt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtvwjhipxn.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gthwquhdck.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtwlmgidqn.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtpiqlwgqz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtfpzfqpbu.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtsuhfrruj.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtncjbyegg.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtngpjkawy.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtvnlghdni.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gthufgmmft.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtinstbxng.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtaeusddrx.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbzbgcrk.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtluzycftw.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtmlytsind.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtomkgtrns.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtvtnwwprn.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtpkoahfea.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtexmgufww.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtxrxiubei.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gthnqfjmir.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtyzftidnx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtjrxrrsvd.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtnntmgyzp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtrldbcczm.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtpadaozgl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtztfrkczs.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtjuuxrnud.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtqxoldxat.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtjkgxnrxc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtvzxqvagd.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtjbwtlvop.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtfwyrwwxw.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtmatuqoyl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtywsfhfaj.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtvelvudfj.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtrhnncuxu.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtzcaqjybb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtququzaqs.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtomghnusf.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtouwnntjc.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gthendwvzd.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gtqlzmmhxd.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtbvukevtu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtdtqjkedx.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtgfubhocq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtoubhkyyg.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtlgrbdujt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gttditchgh.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtblogzavc.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtfvpmavwg.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gthzomgaxp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gterpqolxc.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtokyvdwsw.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtqpdqrohw.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtdoyqbznx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtobzcbpsl.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gttjtlfjdm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtaireaoqc.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtmqghzhwg.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtsaglarku.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gthzkmueaw.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtmikggjqw.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtcahgvhwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlcsrwuys.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtvlnspelu.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtjcmoutik.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtfwlpenid.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtkphhoncy.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtxhdbxbkt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtsupafuab.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gthznvomjy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtvxvwitbu.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtqacowoct.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtuubquyzi.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtvcabflhv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtuqwygdcz.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtyiqsthur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtbhukmjtw.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtcohgwstt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtahiaazrv.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtmqzvwhib.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gttreczffz.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtfsewulju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtwbguykql.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtymlbbfgo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtsyeecmhf.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtkfaqpkip.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtknuchvqd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtltvifgbg.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtbfzlhkii.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlubflihj.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtflekxciy.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtrjjhjdnz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtheqoaqqr.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtobzwbbgh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtvhitwqkm.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtrcvqimav.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtkgxujntu.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtohlonebu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdawdyfxh.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtzmdccqxx.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtzamwldvx.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtrbpycmih.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtinewdkkz.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtsnjsyknt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgfeyaki.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gttrpeyrjq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtluajknok.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtjbxyqxkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxaaxyxz.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtcysygkhr.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtosrugbmr.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtpevwwrvb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtatihhqvi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtsqgdcgew.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtooaawtxl.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtjajvmvec.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtykrozakc.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtkgdnmsog.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtikxabybo.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtkfxkwwyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtvjogssic.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtuixaijxz.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtfbrfpzmk.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtffcqhpxx.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtvzcuxerc.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtruhwygkv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtpdqvzmek.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodhkuiqj.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtucevgrij.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtawjlvenh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtfmkbfwex.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtiltqcqhb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtniwkwhsn.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtfekbivpi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtrextgysd.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtwdwsqdbc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gttwlzjzyy.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtxszufjsc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtvtfkslec.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtkotdfiqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gttwmgsmsa.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtedqgxclm.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtyrlmplvq.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtpomjnrmt.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtihbhkjnd.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtusiuumqi.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtaylhusfd.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtzskrxctr.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gteulloptd.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gtookrqmps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtxalpuauj.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtjqoueusv.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gttlsztvlr.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgezattsm.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtrnpkwxtz.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gthxseucbk.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtcoshismd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtjmvepyit.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtpinjlzbx.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtmiygttox.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtkkuuqmet.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtapdpfrob.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtqtpjspxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtgwtffbcs.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtqdsypwxn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmluyxagh.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtmcrrgezs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtguoxkjuo.html


<!-- 参考信息 -->