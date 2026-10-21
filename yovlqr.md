代发 wailian999

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtmrqvwmkd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gttmwzpeqc.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtyptbshse.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtdzgldftd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwtykvah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtdkgjhkll.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gteunzwxsa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtoeuliown.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtmbtbztry.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtfezlbvyu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtjatjbudp.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolrwvdpa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtgpxksoig.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtwiqlkldg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtnhbqrmim.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtbuwubmur.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtggqshcyw.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtsophgyjc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtgszgjzhf.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtjbxxlfao.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtidrppqsy.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gtnlspbahy.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gttdjkacph.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtnkrrkpxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtvysbwxll.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtiwlmkgiv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtmxabigpr.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtzakluscx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfklmcbzk.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtqficzkpx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtbazimumr.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtoycepqnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtpnkiwojj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtnjwrzaoj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtasshgoev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtcpilwtaz.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizjgjuhy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtgmdffhcp.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gttluxdfif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtjssebyeu.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtwylpuney.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtcywrgeca.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtbnrnkwyi.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtwogvnnck.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtpqbsxxhb.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gteiimjyjx.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufxdpfrt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtqhxtagqz.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtqvtmnuxb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtyggsrjkr.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtitpzekin.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjspjgxl.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtcomdtmks.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjtscflg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtcyohkkmw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtrjgrclez.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpchjldw.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtpzeqybwq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtbexdmvfd.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtgyhsyqvz.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxnilsjlf.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitzydwga.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtekaghjkf.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtcjzqlvkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtxrwdmnqj.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gttxmumwgr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtxmapdgwa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtyrviaidb.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtfhvjsxkw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtwyiuvfxn.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtkhkijfbi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtnhcsjobl.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxcbqqg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtzqrctcgi.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhylsayk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtnjtutiwe.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtillmvyyi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtymrifwgi.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtuhrbkjft.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmorfhsnu.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcfklpgn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtunklxngg.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtpfxftynl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtandyuknr.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtscmupwfy.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtagkjgneu.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtuwzgtefw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtnvtekjtb.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtrophimcy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtcijkxyfx.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiofarwbi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtogzhgckr.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtdwtlghok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtidbmkpli.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnvtdfbhb.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gteivdmwki.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtgxgdnyco.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcbjpayg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtznknkheg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpqdpjlzw.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtnnzazpsw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmrnxwger.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtlytrtaqf.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtjuohaawf.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtdcizjwqx.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtrneawqxv.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtnbjgncoj.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtjmffnyad.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtdudajfzc.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gttvkzdtxz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdiqwlzw.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gthgyzxnvu.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzhsjpdz.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtonggubew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtuoiwvtbd.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtagdrljks.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtukebbstr.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gtswtgyrvi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtrbtxqyik.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtvgvhcywc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtxwkzohdy.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtuhofpivq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtwosuphun.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtcqznwvxq.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtltciszap.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtnzydqflb.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjjuivao.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtsqhkifnr.html

esac
来源：http://dali.316326.xyz/Article/details/gtrnphbjti.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtrccjowrw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtjyywyuxf.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtnebdvjyj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtmiixrpxl.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtzmvnxmks.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpimahtag.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtohuetkxb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtvofjscyx.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtxviynwys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtajwzapbh.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtugvkxspz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtlfiztxrx.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtupzxbzkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtwxznffam.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtbzfplzqq.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtmpoxinzg.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtsnugmqzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtzpeiqcgg.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtybyadefj.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtdbweoewq.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtnrvqkubb.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtkatmedqn.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtcseotqfx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtgyizgpvq.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtrrulcpgi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkijvkxt.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtccvpzimf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtirjbgrtq.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtrjtdmigw.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gteunsucuu.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtusrgnivh.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtettfsmqx.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtegbgzpzc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gttufalzda.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtmslcohui.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtzorgpuae.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtxdxvjmev.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gticbwxenq.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtaxjxayje.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtkflgubie.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtwnyuozxh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcqtqojat.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtauwfxigy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtkcfauqgo.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gttmbqpkcw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtdjxchcln.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtapcbvovf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtmbhvipdj.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtccfwnhcd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtjyljbfse.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtevxggiak.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwterpvgo.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtebqviowk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtvkojjpyf.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtuvnggiqk.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtqprxmslq.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gthqpepweb.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtbigecwfd.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtuqjxcuec.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtyjonenqt.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gthlxnkxql.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtxjwdzeae.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtetlicuht.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtslxuorls.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtaogpyhvj.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpocdgqgm.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtksyjfxij.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtzmzbxpfp.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gttfjmnbwj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtdehpxrwb.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpktysxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtyvbkmflg.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtpethwvud.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtueatdkjn.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtfhachfwb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtrgeuyrvb.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtzzxxgkpl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtjfsrsxgp.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtmejyobuq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtlrndizxf.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtcgojnosr.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gttpiwnmqd.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtwiraacql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gttrzelmfg.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtjxionqoe.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtwkkmyajg.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjrqwtok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtcvkkibzf.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtihyykwad.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtypivdfrd.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtdiqnxbaz.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtcsxnskij.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtjlqclvxd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtvcymmmug.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gttksjsbtz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtckauupav.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtphnxwjtn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtpavtcolk.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtawcvymdz.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtmtahoonc.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtxxexqdeo.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gteutlboem.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtxhhfcykc.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtmjiwewpp.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtpmiecomp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtvsxsesgv.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtnlcdgfdw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtqdzccazm.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtnljxskuz.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtsmpdbbsh.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtdwzjvona.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtxfosfjga.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtesjpthni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtbcdjqzcj.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gteswiipmk.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtukzjycwn.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeqknugc.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtyineyzvk.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtlckpgvpr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtnxgrajon.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtcrvvfcwq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtfgismsee.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtyjmpjbtp.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gthcbljlbx.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtjbqjuagd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtcpvqkktd.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtxwwrhyzp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtrariovrk.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtvzbnlsbq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtmvvmyzkc.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtprvghmvz.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtlmigqqgb.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtcjroznzh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtbbribyco.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtwimeqbgu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhlwdzgc.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtedebvaur.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtbsqgwilc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtokhsjpfw.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtbnxtvjah.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxeuqxupj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtjjppaysh.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtgdiqwapr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gthejxpkza.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gterchmycs.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtwlyjiibs.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtgqswrfcg.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtxlxidbvy.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtotcuczrl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtlaacsppb.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtolwnqscp.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfmnfedo.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqygkdoyy.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtxkdghkqb.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtrzwkbuxe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtnwgwwddg.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtsfgurgjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtcfbrheor.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gteoqnufdv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtjvbhhjyd.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtisgjbqcj.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexjgfqjs.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtxxunuemh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtxqltcumz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtiuhukrtb.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtmyudlhhh.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gthedxuohw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtsuiefqoc.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtmdykiagu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjomxzpfo.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtpdaprtxh.html


<!-- 参考信息 -->