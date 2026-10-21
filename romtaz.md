代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtxslnebjo.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtjrpminue.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtmckhxedz.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtjxgcxfxt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtlevevuqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtgvwurgzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtouknkhdz.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtqdsfrhuh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbzlafifl.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtotlmadwz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtcvsbdfsn.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtxugawnbd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtxrjnlrsc.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtbybvaubz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtmgulsptn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtrhcohbfy.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtbhckzluo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtzakorpli.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtbqvbzyps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtunnjbcfw.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtubkhzsdc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtswjiqfqp.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtjnyqvboc.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtvpruuwpz.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtkmjvlxev.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtubmiusdi.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtgarvdesz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjelmxucf.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtutrofhcp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtcrwcrlbe.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtpunmmajl.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtglbpbbnj.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtxeukzhxf.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtadbsbmkt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtumpqgtdp.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtairobalo.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gthylojjig.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtnknayyjj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtvbtvjaat.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtlywlvdjx.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrerssrie.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtxnjyxxed.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtwojcwsem.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtmizixbqd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtgvddvjzv.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtmgvciasg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtelbgtdll.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtiubkkwos.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtopravdve.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtirembbie.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtokyujvjo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtuwppojxw.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtamumtvlk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtxuswmjan.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklmpvwyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcetqfomd.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjsngdvv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjuuqvlod.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtfolxqmif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsdkjkeqt.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvvfgdzb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtosezokaz.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtrhqcinhp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtvhholqob.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtwarlzroj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtlbbuswrt.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtwqqnryig.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gthtgkqljj.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gteipbhycy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtirollgct.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqshnrbiv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtoweymjna.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtwqzaiylf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtsimdljrc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtucvmbwlo.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtbjmsmbvh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtbwrgeqqf.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtlwxtqktt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtuhvnvibg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvarcycil.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtrsrsdwly.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzxulygsj.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtqrbupvwg.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtumcfpyrz.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gterwjepxt.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gteeaxwaqs.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtuoxarvdx.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtoyxepqhi.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtzsihwnld.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gteirmyqcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtxhkokswe.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gtkdqnnfne.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtccaborjx.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtjdpfzwed.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtvlpqwbtr.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtojdqrfto.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtepbxdtnw.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtuklrnbly.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtjwoqyrdm.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtwymotjnx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gttsgjhjjr.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtuydybadj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtsnwzyyfc.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtftucxohj.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtaeadxzsn.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtrgdksepj.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtrjfuubbu.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtuxlkxamy.html

esac
来源：http://dali.daxiang520.top/Article/details/gtnuqhakqq.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtwpxhqzru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtbvzdkbnb.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtbaohvowx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtmichmhim.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtewoujcfo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gteriwlipl.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwevusqlg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtaipxscdk.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtdrwmpfbd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtulrmmruq.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtizcidqyj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtrahjwpfq.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtrfvdvfbs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtzefkwznp.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtitphcwjd.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtdxgxfsqu.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtnthpnlin.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gthpsbvakn.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtbjrjtopq.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtddmzqlpz.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtgpqmjryh.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtaiucawvy.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtauzjjpew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtimdnfbnf.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtzlnxcdox.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtzhbejizl.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtcbzutofd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gttqdummji.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiysawjak.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtcqghaguz.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtqkcxkvwn.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtfrjtmmdh.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtdknviefp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gteagkjolh.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmxlunxwp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygfbrpxi.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gthxgzmszf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtuzvdrbqu.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtcrmuddyz.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtdtdfgslg.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtggdlyakw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtynrnflzb.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtljindtmd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gttphwaska.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrpwtgqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtdykyyodr.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtyrorzyuh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gteqqdaypp.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtatafnybz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtgbjpjqcw.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtafnvosyv.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gteraowinq.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtvciwpwvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtivabwcev.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtnllatqdk.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtdxmtyfrr.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtjusuwtop.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtjfbkdbgs.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtxbyglkou.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gttbkvlbna.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtuwfbrhtn.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtjymlowxi.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtnswvrjqr.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtlhcbhltl.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtszuvwczz.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gthmyzqobo.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtpayjceam.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtwxozjfak.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtxtdxiemf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtthhuqtlk.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtzgecrlkw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtavwhmyuk.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtrkrsxwkp.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtoqozutla.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gthawfdaer.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowcbvulc.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtjvgrjqae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtnhpewicj.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtgpqrwwek.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtmbiueyjj.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtvesnepko.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtbhwzfdsf.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtjddauvlc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtptexlqjq.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gttmwaskmm.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtahrhulwm.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gttsbxwrar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtzjocxahd.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtlqiidlbo.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtuzjlwudy.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtbatezsbf.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtpayjpqnj.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtckgxlmxm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtrmzptanc.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtxgczvcru.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtewshxxky.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlgsjugj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gtzxyglkgi.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtoavkjjuu.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtdnivlmxp.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtefgwowvc.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtzeqljkdc.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtofzeyarr.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtebqkjpul.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtxqntzpae.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtfbhhsjyx.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtgpkuyelj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtgcxcuvsq.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtbccfhcbh.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlesvgpct.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gteyarhtpj.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtlohonsac.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtmgpiforf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtglpfxzqg.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtsunonmkz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtozjiyymi.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtyueuioya.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtrahivjav.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtiirhzgjv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtzacwjdpk.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtczsfqqyk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtfmgcjiwb.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtmxzdcpbw.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtishgijlw.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtifjcrbpb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtboqeduhy.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gthbcqvdiz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtuzvkgdxb.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyqumqico.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtcpwqetyi.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gthtacozti.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtcqgvxlpr.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtczyqrfqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtshaaadzv.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtjpioirct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gttmggscls.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqssmirt.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtksjybdcj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtolnogkjk.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtjggkxaob.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsazwwefa.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtwhrznvtb.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtbvvphmkv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtxwzcidds.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtvewqtqjl.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtwlxphjlh.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtklvxvcfy.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gttmieabdf.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtskufrpsy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtmpsaaysk.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtsfigkmzl.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtuiejyqlv.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtravoevsq.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gtqhhmzxxu.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtqmyrjkhd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtbjyvalnf.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtlesjdlkw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gttzpnkura.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtxuopyxho.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtfomwyhfd.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtgvwnrwsl.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveonfajp.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojyunwpu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtfztwslbb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtbtkcomwm.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtfdqoonmj.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtkyrobtsh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtcenedzbv.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtggxslxsc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtbbvnxgoj.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtppkkpbni.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtokcktulv.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtzckvzwtn.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gthlavicjo.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtltilqfhi.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtqhiuevcg.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtjsuxbwlk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtcjjspzhb.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtnvlrdwfm.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtpagohtfy.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtfrgabqwh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtiyhavtsr.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtvgetqvqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtydinymtc.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtqbzfywzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtunfjekdg.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtsslwjmrq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtaftiwsqx.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtxdzncbao.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtekflwlrk.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtubdtnsvm.html


<!-- 参考信息 -->