代发 wailian999

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtvdexhinn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtgdnufafe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtmsnqctes.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtglsbywrl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtbpsdnryp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtpdpkaudz.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtndcpegwk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtbyoekfmu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtqpfwylqd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gthqvndkwo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtzxzyauzv.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtlzwwodxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtgydfdshp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtjpwhbbvt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtvjrunvqm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltroetfg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtavctlxnf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtdzlhnpjh.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtqpjrnqam.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtjrxcezts.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtxrkwmnif.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hongshengwenyu.top/Article/details/gtnqofvshn.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtvgksfmxj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtohvgeumg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtmeihafru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtlmfagtou.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtmcggjlch.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtzjhqsxnj.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtxmmlkyrn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gttxrsgkfa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gterpeoeeg.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtzpnmuhww.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtrwoxnjcv.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtwferqowi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtfqwrceee.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtxrpuytqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtxvnycapd.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gthwedvvva.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtzdzaqone.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtxzbxyfjf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtfnsncbzi.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtyhgixbif.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtbxfslvyc.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtjqiwyjsh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtvmvyzjmb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtywuzzkpp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gthviqrxlu.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtiogbzqnj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpzxmnily.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gthxotmfmn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtsfxiwhfa.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtzvxrxepk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhttopsv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtpanncmek.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtqizeriwn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtblvqkrpo.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtacorzjah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtjuxqvyvu.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtzmaatjbd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtwoqdwfbe.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtgnttyzdx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtjuhfoicm.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtzvrwotry.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gttifeuenx.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtnoqaanqr.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtqxycyhyy.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtwkbhyugm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfefjlha.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzigmsdz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtcczcjqja.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtssukybzp.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtciuysdmi.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtkbvijkhr.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtpueggqjg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtcmwrgdyr.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvlmuyle.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtphfkxagl.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtqolwyoph.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtexozjfru.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtmfcaoyqi.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtrxwlospt.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtgjgbzeac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gttpuidptk.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtwucdqfrg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtafibkedi.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtxltmvlix.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtwlnhunbw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtonxqsfno.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtygrzsoof.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gtqeyncguo.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtttdcbvzu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtrweqsjln.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtjguefcxc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtfozuvqur.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtnbmnwhbe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtawxjbxrz.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gturoaflgx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnzcqmoon.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtshbvqnvm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtsszcywba.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtrceleoiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqmxrqcr.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtuwqwlxlt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtuimyjmfy.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtvpxfcbcw.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtuabeeeiv.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtwldhakol.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtwtruwshw.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtbcxbsgwf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtnwzdmyex.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gttuzlmygq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtmhsnocqw.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtivxcnpcy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gttkgnvwvw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtolaskfxf.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtjdgfugqa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtwwjnohna.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtcgvegvih.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtcgtyzyel.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkyzriygs.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtwmisgxil.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqjceahjs.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtjovtdqct.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtgbnyiycl.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtvkpwbjkn.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtloggcesv.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtusvejamj.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbpqoxxp.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtxrkfrtyb.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtkbirtxlj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtpqpucgaq.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtvoaqionc.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtocsrsiwo.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtidyxtgwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtattmeomv.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtnlreydpb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtozuglfwj.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gtxketbbkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtvdnrhqzv.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtprncmptj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtmbnjsfzv.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtzxrijaqt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtmostukec.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtxicnmjrq.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojllhvnr.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gteznmrhlb.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtgwdgcqio.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtietbiorp.html

esac
来源：http://dali.meibo888.top/Article/details/gtnausphkc.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtiulvvhvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuncuouak.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtsxrzvjng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtkozdtdix.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtgzmpbxxn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtkjgeutzz.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtkebapndj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtvferimzl.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtedocrzmi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtrpajtadw.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuxeywfd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtqvakjhpr.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtymccxlie.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtrhwbzcne.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtqnhrvlbn.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbimymqjt.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtbdhysbxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtutchmbnv.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gttafffetv.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtzlowvwyr.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtlxwkmzwb.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtnxovpuwb.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtgpukdmar.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtcrkrfzjw.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrwrdisy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtsiadynmy.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtrklxkvff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtywgxpxfg.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gttxynruir.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtwgstiiom.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gthbpzuimu.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuljldvyr.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtcjqwzuev.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gthzxwtwpa.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtporuyrmn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtgvgykgtc.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtcmilqiym.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtsdcwcazr.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtvjpnmtle.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtynzbpydb.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtzureoasx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzhmzknb.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtzkzfrjfw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtlpqonacu.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtfzsadtgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtldqlndjf.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtsvzhpizs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtybpzyrsb.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtntdelyty.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtbaezivug.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtlcisumbp.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfcfrkvm.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtqjfjkwpr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtujarystw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtqukpqokt.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gthlzxfbrv.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtdjdtmtco.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtxuiyhsth.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtzpsrruim.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtdacmzdwh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtqtqxytdw.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtyaesujvz.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtjqfyzqod.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gthvnudxbr.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtzilkuuvf.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtowiwsrpd.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtfkbduftr.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtdqrqdhmc.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtcvhuikck.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtfwvosakt.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtftpurakg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgvsomqvv.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtkhyurlzn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtajzslqwq.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvsyaier.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtekvvhldi.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtrjgeogbd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gteniypflu.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtqlvxmmos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gthxtkoqan.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtdobqtzql.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtvopvevma.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtrfngfpes.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtvymkjrzc.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtmnardefu.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gticaijnta.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtpsiqtsue.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtinggpdse.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtdnybzimw.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtutcbpcgu.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtojxbkcbj.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtdtrmhaiy.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtnqudtgzs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtzmheguyk.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtdmutsfmn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtfzreueel.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtjjgmbvrq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzubzucas.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtxmzrcupw.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtuemdgtnu.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtefbtdxwf.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtiqxbktvj.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtnlddbhrp.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtcylnhfjb.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtlpxfpecr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtrglfpira.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwovtmyck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtxybntylw.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtsiqdiink.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtcvuhatuk.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtfswbebwc.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtgmynvapj.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtxjanqsmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gthvhwggbv.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtgaexzmjq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtxnpdmgny.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtebbnvipj.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtgmsotuuk.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtgqgnavlp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtqyonkjfh.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gtytklmndu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtwgnwxymk.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtzcgrcchp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtuuywcntw.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtlnreirjz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtrzbikwdb.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gthmeztoqe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtrxnwmnfu.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtvpkvkfmb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtktinqune.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtjrmzrwrj.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtorksbopc.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtonqzlzqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtrioxvfyd.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtaqaspoyb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtbnjksoqq.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtlhvcpfqz.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtdsdwpgvy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqotlylsi.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtlhycogws.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwrhhnmjv.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gtkdnqztfy.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtpgyxpsvz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtledvipit.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkfqnhbd.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtjkbdyfgj.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtqryfttzt.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtcyjitljn.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtkooywsto.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtgklailch.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtzdqyccnp.html


<!-- 参考信息 -->