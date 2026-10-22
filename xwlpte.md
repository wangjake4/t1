代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2sylchxtj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gt2rdsoudac.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2qyuuyhjb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gt2vkjtqpfl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2ehqhnzaq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gt2ebcipgso.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2uzndrqdw.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gt2wgipefpa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2dgexawqh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2tarizdbr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrbbdenm.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gt2bdlqzwdj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gt2iepzpwck.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gt2mmazguij.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2drtqglkn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avmbovte.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swjwpvhx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2yllhofbq.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gt2lhjeagqx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmoztjdi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gt2gkmnetdp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2pgigmzdz.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gt2xlnottko.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgegfpnx.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2gikgkmwy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2gmtqapwn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gt2bbaqvhdb.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2fomwxkzv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2xjxnofzj.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gt2rybawpwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2fjjsluer.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2pugygxyz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2judapvtp.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gt2yxerjopm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2kvomzsbt.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2tufmzvgb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gt2npjjbfjq.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2xwuecpyk.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gt2qysruclg.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gt2daupyhyv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhgfdrum.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gt2tnxyhlre.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2yrprbitz.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzirrdgb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2gxhkgkrb.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2vdrxkpsy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2tlaeozhv.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2wlbhdwla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2cskndlmu.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2oqlsjipg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2stdtjqlo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2lsjdhfwr.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2zmekensq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2cijrzjyy.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2vpulupni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2mepdydul.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gt2eoyxvyqu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2qtvexdmw.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2gpzfdxdf.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2hdehlhsq.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2fgkrqswp.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gt2zxhnxvrn.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gt2tsdtkwlm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2ukwamgxf.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzrhrwpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2yhpnzzyw.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2cbmfpsyn.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gt2cpujvren.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gt2ojxnwxie.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2wlnjvydb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gt2zuwzthco.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gt2eraanqau.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2ppzdpcdw.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2owybyqhe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2ddfpeqbk.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gt2dffenezc.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gt2ckxyigtq.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gt2kzdqgxnf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykmmcgdw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpsqwdi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2ftqzenun.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2enqysfuz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2vzlhmpks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2vdjejctk.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gt2rwzhmadf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gt2jgkuxzyl.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gt2csdetzsz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gt2umurmceh.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2wqyiouxh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2jbpumcbb.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2zsuwakcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gt2bbqqxsth.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkmotdtd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2czimjewm.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2kbsftamj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gt2fmfvmxmr.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2gjmhvfmk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idgfcjts.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjvffian.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2mvjaesze.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2fzleygro.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2yjxzvqfp.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvczflxc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lutwrpdh.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2uzfqkttq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2wbcaxnem.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjoocriv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2xdlwvrxq.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gt2kchuzpvi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gt2gfnkeyxv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2svcloxph.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2dqrpsvcp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2lkfnrxtx.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gt2qynvdoye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2cylabnyo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2taxptsde.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2zzwwylvv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fkaxkzmy.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2elcweypx.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gt2oleamjfh.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2avubxszu.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gt2zkkcenzj.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcvmtill.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gt2siucdwgh.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gt2ncbuyjeq.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gt2bmmrfnqv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2mbqyavce.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgwcyxet.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gt2mennafki.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2uizfnfmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2rhujvqxy.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryruqbip.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2xbpxsjkl.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gt2pvsufiuu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gt2wzqpvyll.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdxkwitz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gt2issatymw.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2qobuardy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtagmlpx.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2skabowvr.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2lpmktvpx.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynxffwxv.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2wtxnithh.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2fnsbtblw.html

esac
来源：http://dali.pycfn.com/Article/details/gt2rkuftmon.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2dpaqvunv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxbphwjl.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2nkyhmgrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2ndjreveg.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2pnubwvlz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2byhaltds.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2hlrjasrt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2sqzsqnuk.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gt2xhhryzef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2cdyyyouk.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2kqzejbhc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgoylboe.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gt2ewtfcxbs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxwagptr.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2tqrycrnw.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2dmtzahke.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmbgbjxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2bibefeje.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2tdtrymji.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2zyjuuauw.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2sdjfzgtb.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2txnokvcx.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2pgsdkkhf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgejikoh.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2cpjeivvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gt2wfemsywq.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gt2bmakoopl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2ocedpomz.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rydwwsrq.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2pcfhcaci.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2vwhrfoqz.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2wgqednlg.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gt2phqtgpqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2ntvisiby.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2pxnjifla.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrllxkga.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2qntjgmwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2zjuuvyih.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2vssrqlyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2liprjreh.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2sbcpmdeh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2gmguhdfu.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2rnresjuj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gt2bustwbpw.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2pibnualw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2eplscndg.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gt2appcscvp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2xkuplqna.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2zotgopcu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2yinbyekg.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gt2goqzbslq.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2gqznbgbf.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2ozceuagl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gt2memfzinb.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gt2rokpvckz.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjfuglwh.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gt2udaqdvie.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2qjqftckc.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2ubovlsbh.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2tflizmyp.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2cplapkve.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltjowtnz.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2svxzayfn.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2dxfbpuaw.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gt2kzpqofep.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2nzpcftti.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gt2nrdeoevi.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gt2updfdbcm.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gt2uhjpeaar.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2huxwhpbi.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2swtvknrc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2txctsdrc.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2xiwtpqnf.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2hrfsclnd.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2vdlaqfay.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2mhrqhvzp.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2euywwbxu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2szzypkcv.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gt2qxalqpmy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2bzjckwwy.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gt2cvbsenra.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2xszhkvbh.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gt2vyowfcsa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2wojcaevc.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2cvzsmwid.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2hpibzppi.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2brbfurbq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gt2msguffxp.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2jhdicaez.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2gxlexklx.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2zuehsova.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2ykooaqgs.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2dskryqmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2gryvwzni.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doufzmag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2wtapkrmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2fecsywkx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkbyiolj.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2gakahgzs.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2gtttuqhc.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2tesxgyky.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2bzuoyvyr.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2jxmhbzij.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2mczcjfkk.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brgcvyaw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gt2nnoqbdqa.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2khvaqyav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2eesaefqg.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2premvpmq.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2dbtfpphy.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2unxvesrz.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gt2oprvrvqr.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2qjomkrpx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ygmsekfc.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2nsgsmiei.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxmobjnd.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2hsgwjujr.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2vqwjtgbl.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2yifvails.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2ibtzyssr.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gt2mjamdtgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2orqsangf.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gt2sbxoefbf.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqeemfsp.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2lvkptfld.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2jsdokpdc.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gt2yfzdsjuz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gt2cxbgrnto.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2gfclwznd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2rnkrytpb.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2wayocyuz.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gt2zxemljkg.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gt2upkeqznt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2dijbfwmb.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gt2skosqdbl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2qkksybhj.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2fmrkuzgm.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2jmqzahjn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ytutccbi.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2onbdkqqr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gzkbnedd.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2jydjdeym.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gt2tpzakqxb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2nerglwsv.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2tdssqtoz.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gt2rrhsmaju.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2bxyklxmm.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gt2azmhqkqb.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucyhkqun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2sryhlltb.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gt2idttjrsi.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2bzkyslla.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2nsmnkblq.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2hzffxipc.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gt2jbdtuboy.html


<!-- 参考信息 -->