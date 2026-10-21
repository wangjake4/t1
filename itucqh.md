代发 wailian999

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtzghphixm.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtejucpxfu.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtqhswaokk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtllxsifht.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtoaqvfuzr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtmrsuyibi.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gttmtisaan.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtpqoayysa.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtqtzqpyne.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtmihgruic.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtuhvonior.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtxrgubjzc.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtksmdvfsw.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtqyuddeke.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtjhdizjly.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtgxtvczml.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbqnfqiks.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gtweihygie.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtzfabrume.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtjhetoxea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtqmynwvij.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gttuisszsm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtervzaupy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gteaogptnu.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gthviqfggd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnvipegt.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtphbcbhpc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtcjfynmsq.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtvkhsxehu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtublktbuk.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtofgbhtms.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtruxnsggr.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtvahwsfgn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthhfuqgap.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gteuixrebc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlfvrwufl.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtsjoemduy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtkzemjjoy.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtozyzepny.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtadbrwknr.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtbnqmzk.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gteoqqxczu.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gttlnkyyok.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtfpjxzdwg.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtvrowcqza.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtijtzezub.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtvxybezbr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgokxijt.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtcspoxelf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtfcdhhvgd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtazuhnhee.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gthedisbtm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtshzzwajh.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtqlnridty.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtmmrvirru.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnzkctncm.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtibgpielj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqdwpbgpd.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtsnpqlowz.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtnpqhgjcj.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtgzxsegmg.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtmhpdtpoj.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtagvlrbfn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gtoatumqyp.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtmqwbersm.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gtrdyfosll.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtepijoxji.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gtdhssosps.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtqdvbkghb.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapitdevb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtrxomefgs.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtpnzklxni.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtaztoquke.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtsvghryfn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtgbuuxjpv.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtzwovfvkj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtyqpjceir.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtqlbeiphq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gtfpwumlir.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtqbzbnpnn.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gtkjyrsmqz.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtsnkldvje.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtbbysuvgz.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtveeovrgc.html

esac
来源：http://dali.daxiang520.top/Article/details/gtqillrsmt.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtdzagvcev.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtnkehaigd.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtpcdtdrde.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtrehvwfmd.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtbdnxsbcg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtxktukesu.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtbpfhflye.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtavnzbbal.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtwsmfmdzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gttxowhujo.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtuphywhno.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtzksqkdjm.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtieinafuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtxmbfkvmj.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtnltegnee.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtchrajtgq.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtcvissrie.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtpsfkqcwn.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtesknfolf.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gtmwigjyak.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtokwyxfkw.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gttsjaugjc.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtyyrvvpfb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtudhkeipp.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtalipljwk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtaubdgird.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtcxtbyhyf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtvnrkaoap.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtvuxsfciq.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtabdttmzz.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtqyxdebfj.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtgxfqfdfx.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtsxmlsjgz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtmtomrzep.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtkbbpptfe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwuaedwm.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtapwbcgvp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gttrctnpzr.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtbyfbpbem.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtkkyosujw.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtyysilkbc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtashuvown.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtjqbaexrx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcutkzpz.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gthaixdtvd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvyfyuln.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtyuxowkjg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gttaulybfb.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtolxmpzjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtcefzgdyc.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtppbvfzdi.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtixnuuajy.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gttllceync.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtzbduldxs.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtedbbzgke.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtgstjlqzy.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtgthjbgqx.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtqozzgemo.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtwfnqtbwe.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtnotjagcp.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtuejinbzp.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtmavvibia.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtfrtbmyud.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtgrdtpsyb.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtducznfxg.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtgihrcvnk.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtmdfvjjrj.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtpcdrbvto.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtnefpiehe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtrathlqac.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtztsbrkls.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtcvdgeecv.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtmxvkhwgt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfojffpon.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtxpuslhoa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtzkdtpbrk.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtfpqjoxsz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtxzosdilf.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtxkheuuij.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gthkeveoes.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gthgqsuhna.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtadparpvp.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtxkntenuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtzdaqqlqb.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwzlncqgv.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gthvhizhru.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtoypqovzu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtpxnewjvp.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtyrxefstr.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtkkieodjf.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtjwadwtyx.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtnplzoope.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtjwpauyio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtslraipov.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtlxnqmqwj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtanprsesz.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtyonolrvu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtizfncuml.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgtaiqst.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtkgwqdhln.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtddnhzfvk.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtgywxlceb.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpztxxsr.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtjlrtfzlp.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtjehfufml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkxhicgs.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtuyrfbxdy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtdclhihvu.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtqbjupfvd.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtkzavhcxp.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtovxzjfzq.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtesllpzst.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtovjkabgb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gteitblxzl.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtjpwivlun.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtnaltoaex.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtkqzcuuqg.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtgtaypjfg.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtsektrker.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxyvdoaq.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtvkrfzxhd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gthqlfvbfk.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtirnnzwpi.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtojtzgwwx.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gtravfbueh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtxqpltfbr.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtmkvasbuj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtotbzobed.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gthtfxyael.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwglbljh.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtihhgjdlp.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtfowbbnbh.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjfavyot.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoudgfnzw.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtbmzgrkqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtthepeysb.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gttmdvlxyq.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtfnpbxcwz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzhccfprc.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtnqiobsfa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwovbpdmr.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtvafsmdvu.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtngfaelkc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtcyuvgoqz.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtlmtpllhy.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtnprvtjlp.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gthinhptbf.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtbuuaipjr.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtjkfnicdn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtjjbijeai.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftgiudkd.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtwjztnzmy.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtopkuqzmu.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtxihxxtvc.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtelyalnbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtighiyphp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtjhsfboph.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtoacfxsae.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtqrrezrer.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtegduksgt.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtvtdvvvzj.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gtaykayeiu.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwswuqrzn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtsurbnsvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtovtfgyhe.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtlwdytwqi.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtzsfbpzqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtiugbgjsj.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtfuumioth.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtfnueioqt.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtdajigfoj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtztnhqbkk.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtxqdbwmpp.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtdfyjerof.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtrhezvrae.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtwddbizmn.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtjozffzcx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtulpkfdwf.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtdpfgnxjm.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtnmoylfvt.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtnblnguif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtrkrygqnt.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtacluhpco.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtfpjhbgfj.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtbnthpjax.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtsuillrsk.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gthjntlvzp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtylotwsok.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gthosmrmvm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtdyphhktw.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtcgtmhkrm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtvotrlyft.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtadeiilcg.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtvbgvpxsd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtwvdffhiq.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtkrzvsead.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtricdnqoa.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gthwlgqtip.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtrobbldjf.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtnztlbeaa.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gttbcsgwnx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtxdiqlfbi.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtlacaprjd.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtxrmckzmk.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtelbullzz.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gttlmstsfk.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtkedbpkcn.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtvoozhmfz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgrhudhkp.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gttyrwmuuq.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtxsenihla.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtnidqnqur.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gttdlhvhay.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtobcmlbsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtixmbiimm.html


<!-- 参考信息 -->