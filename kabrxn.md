代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gt2jecjdxqb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gt2qnkbysnm.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gt2eueeixqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2kqmigvlg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qybkzmnc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gt2ubfncolr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gt2mtlhajcl.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gt2xuapsujk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gt2idscugkq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gt2rdtusayh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gt2honnwysk.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2mozbldpl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2ptzsaxfv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2cnzrivfj.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2kecudyzb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2fexacxsh.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gt2kvrvhepv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2htyqobdn.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2odhymupq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iobyayme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2jhymavhi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2hvpkrlbf.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2efkficnm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gt2ykwtydof.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2lvuqbldj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gt2stdrkena.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2gamkewgm.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2ubzorddo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2yjcjxepw.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2djlivjly.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2aetfssrk.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2efhswmwn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2cdwwijzb.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gt2bkxkqsha.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhqifcmt.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2lsylviff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gt2cujsimlb.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gt2elyzgmny.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2vemyxtcj.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2apvjrskc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gt2nipweiir.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gt2ayuynpfk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2ujtmizbh.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gt2xnzqwlmr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2fieyrreq.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2qtkjwdxv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdofmjmm.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gt2vpwvzgcz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2mjlagvbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2mqtsjdqn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gt2buqhwehy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2dpxvyure.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lysajcqf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptamclxy.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2ztuxvqsf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2rppisorq.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2tmoujewv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2ohpgezpc.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2irmolqeg.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2ufjcjcbs.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gt2ptekwbzs.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gt2rexpuvxb.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2eaohzzbo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trzizphj.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzbkecbj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gt2pfnsdcbd.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogedruhf.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gt2iesnsgrj.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gt2fqubataz.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2tfxmvopt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2thssyrko.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2rropkrkn.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2fzeasyol.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2vhkpnkyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2hksjxyyq.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gt2qfjeuywt.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2hhttnddw.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gt2xpozjleg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2wvqixkgu.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2pwenlrkg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gt2jjwonwoe.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2xqwlbgdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lggjzojk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2kobccxdr.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2pliilwfb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gt2tnykbott.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gt2stzicxac.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gt2ejdperwo.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2wxsjanqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgmcjakg.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2ccziultp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2vxnqiaeu.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2vevvufdq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlfmzovr.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2quotaxyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2esuzsvxk.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gt2ejgnkbpq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2somhwbuy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlnwtal.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2ztpirorz.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gt2rnbkzrxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2mhzxtzzv.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gt2stvjbvan.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gt2fjihkayy.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2umisfdxs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2bfdriysc.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2tslqsmgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gt2vaajattt.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gt2oqqarrsm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gt2zpksqlwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2rfvtpfeo.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gt2rkavnxdh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmkqymsq.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2nynfcmqx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2qfmmnxko.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hcjfnjjl.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2lgbclwpv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2djytbzkh.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gt2abwqjqwx.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2lobcicnh.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gt2nanhfdql.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2iiwiqkkp.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2spfookwr.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gt2pmpbltoe.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emnueuuf.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2ububuxvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gt2gxfjsqpm.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckifpzex.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfrmceaj.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2pgxfjeub.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2nfrgmald.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2vwkovnkr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frwrnlqh.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gt2kudxtdll.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gt2faqdjida.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2zcfcrpkg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2jbvgltma.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gt2kktobtkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2nsjxlohl.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2svzlswuq.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gt2hujfilqg.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipbzckey.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjxeqmok.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2fvxfhjng.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2qlhnqvyr.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nclmtuqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2ghxaisuh.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2zhjobqsa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2mhdlidyw.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lppjvzkw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxcbfkis.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2latynsgk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2tvveegmi.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gt2miicctft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuisvjnq.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gt2pczzodcf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gt2qjdvatye.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gt2ywomuzxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2uagagpsg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzyafdu.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2iqkhiynm.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gt2xwuvxtra.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gt2bibejyjn.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2zfggzmcz.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gt2jnhitxur.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gt2dbztpmpd.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2nxjhnqip.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2apubmbcz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2ignpphax.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2phfvoffc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2kznqtscf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojfxfqnt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2vdvuatmr.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2sxddrdcx.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gt2llcjnkfz.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnjjjiyc.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncvzgays.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gt2colpyond.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2evevztqp.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gt2vxiuztho.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2bmrvgftb.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2yefjrnfq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gt2cotwoeqd.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2urlsyibz.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2trzlzhjk.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2vtcxwvta.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2obtydxuy.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlvjzxsy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2uezqaxmp.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gt2swnxlruc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2vppmkvig.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gt2xhsnutkh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2kofbspim.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2wyrcypyp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2kcxaxrnf.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2dcnemcqa.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gt2kwdsudtm.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gt2cpgwjnfr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gt2tnikavcz.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gt2rufbxzrg.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2nnginjzv.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gt2rqjyogvs.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2egxjrrsc.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gt2lpptaybm.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2wvbwhtss.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2nlarthxg.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2hogenvvb.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gt2qjdwkjxt.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2zknpkpzx.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuvyhqfz.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2bfsknhap.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2gigkqtnl.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2rcuwourb.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gt2twdwjdvw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2jtqpmefz.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2wxohkxxq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2nnpxpsmc.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wurxdkqo.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2zeodjpgi.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2ssebuwad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxcfaibr.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2uorhlnix.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2nciezmec.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2bbeeluor.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gt2dggckrtw.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gt2goywnqns.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyngygew.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2aaguzlyz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gt2prkraswr.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gt2lypiroho.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2hcdjgbja.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2fntjmyxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2cgxyqgot.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2ytbvfeor.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2tkkiokhw.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2rqsukpiw.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2vpejefpj.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2crxlxrym.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2vnuxvudd.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2nnhpcmjk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyhsfdng.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2nlwsuujz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2puvfihnj.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2weftqkbs.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gt2opuknhnp.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2tcgdpvyh.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2gminfscc.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2pyhmhcyd.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2ajyffzlc.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2uktlrabl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2awqtlnkv.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2ktgzzbfa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2gckxkqsm.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gt2tkbbgxui.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gt2lnpkkmeg.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daodwidx.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2mlsytzcj.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2ijditzyn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2fghpnnnm.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gt2ovsvmvvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gt2gtybkjxh.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2hbgcxiyd.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2swzelqim.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2rlvfkhyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2pzmmaxux.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2doletkjq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2gesajgze.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gt2ulcirlpb.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2gykbljnl.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gt2mployhoa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2athxdigl.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2mjyyiwas.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gt2qkeburqs.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dumcfwey.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2xtvcefda.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gt2oiwtniff.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2ulzskigg.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gt2jnutlknk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2zxuuwxex.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2ciinoydz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gt2ktzrrzqs.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2zerjanyf.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2fxuqbkyh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2czxkcyyb.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oluatiun.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cwnskbty.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2igjlqqtr.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnxregiz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gt2zrcueehs.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2xmvkhmcn.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2apueyued.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gt2oscuyorg.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gt2kikjpdve.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2ppvqwxsw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2ehzybbhb.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2sksvifyr.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gt2avwwndqt.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2uzhassda.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2naqnfbtx.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2qfccnrir.html


<!-- 参考信息 -->