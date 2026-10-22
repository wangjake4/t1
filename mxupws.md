代发 wailian999

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtsxgnvkbe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtlbzufsvq.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtrslfrrah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gthxqpdnjv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrulgdnmm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gthfdogdpb.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gtqeoqlmdf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtlqstjzfv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtsafhdgtz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtatesczqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtvufhtlyx.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gturyahkjb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gttgjodzdz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtxamjvrsl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtzbgebist.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtntwtkxux.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtrfmfujxu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtngdyzgsw.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtvmtbwskz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtnphathzx.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtfmzfxsim.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtorlnomej.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtthszfvpm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdvcnudm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtxstqkkve.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtkpfzsepq.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtozyufrry.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtxsbwrwsc.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtlquwodxf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtsgcmpdbx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtbljyqetp.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtelnwryzl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtrgycqkwd.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtgprxarbx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtjucxdtob.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpjzyufq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtuxzkdznh.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtlqoartzw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtfiyxvqsr.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtotvpzjtr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gthdsndfsi.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gtprkcrktw.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtoyiynurv.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtbauwueqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gttruyvmhh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtjqfgpwkt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtkojjppao.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtgvstdmxr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtwhrkxyrj.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtxwjgfrmh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtyumuuegf.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtakzmvtqx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtbxzaxlxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtnewpjzhk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtocesprwq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtschitsnt.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtwjeqwjsi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtdoclzrzy.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtbcstlbgr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtblqbxwwt.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtvepdowjx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtinhwfrau.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtiuwpmwpd.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyswflytx.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtjglxzaep.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtkaifgcxf.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtlsijozpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzxaoavu.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtlnsuhfpn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtfuecufaf.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtgxtplnoa.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtanwfzuac.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtcazoximp.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gttspvrnpj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtxddakdkp.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtkvxsilrp.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtkorwoccf.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtsujblkrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtfqdsaumw.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gthkjzsxrl.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtuudpvhep.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtkxmgduwl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtycyxoysu.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gthbcxxmzs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkunfyij.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtiildoysn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtbfkcvrde.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtzivncbre.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtumqyrhjy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbhrxawa.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtbqsccblc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtxinhyzkc.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtxmsznamv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gthlhqhuio.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtvcenjarn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtzhzsdjfx.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtfkqefkfl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfoiwxte.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtvwfmbeyg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqsokhkjq.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtxlhchjly.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtgjenpboo.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtgpvyrsqv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnorbahvu.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtfwzhgowb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtojiuphqx.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gthenvmdvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtjchubzdc.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtnhioraab.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtvryghtxu.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtgcvdqmmn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtfrzdtkyl.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtbkaoxmyz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtxbxmkmkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdqkesllq.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtpycialrr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gttnowlvdn.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtmhliksmy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtajccgduc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtoxyrcdku.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtcsxbsndh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtykhqybvf.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gteqkagffq.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtyizhnmay.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtsiyfatmj.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gtjmyvdhuw.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwxgdlad.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtauvqckuh.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtavhuvdok.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtmblacowp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtplsngzop.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtltkngnzt.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgpvyreb.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtbpjpxrgk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtbrreuydz.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gtckmbzfdt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtwiwjtqun.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtdodlejdi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gthltokezh.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtwwqfcixg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtbpnlgkuo.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtisuwziuq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtbbadkkgu.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtfwlijhmc.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtpsivowjr.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtghgyuana.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtgenvjjyp.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtkjuhebze.html

esac
来源：http://dali.yvedp.cn/Article/details/gtxmhfrruy.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtuflpqrcr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtbtxmwbzg.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtobrxrwoh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtdozusxqf.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtmcssvvmk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtbqtnoowm.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtdtgmlidn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtxikphtbh.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtvegjpaow.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtybmvxlug.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtvdnbgvui.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gttzvywkuj.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtjfesdqyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtmjzonseq.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtxkonemfx.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktxztizb.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gthfhdwacq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqssomckr.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtugsjflgl.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtqronthlv.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtzrfyeboe.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtafxvrnvc.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtktoytmbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gthnyzamfi.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gthwrxgwgt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtnrlwolky.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gtsnmzafrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gteiouheqn.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtgzhkicvs.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtihktueyp.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmdwyvo.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtqfykmzmr.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gthpnxfqcv.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtpcxmfkws.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gttmaluazd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtqivxzsvo.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtochjowzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtvulpypay.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtsaeipigb.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gturquvnfs.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gttkmfljoo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtfejbrgph.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtdettrsbq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gttzobemjr.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtahhrpgjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtspaohdvk.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtijbcprap.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gteorxqtok.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtwnccwdvh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtichfrckv.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtdmqpuorj.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtqmxwoabh.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtcimilgpc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtjzgxelit.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gttprqrgtm.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtlkyjfcuj.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtxkoyonkc.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtpcxskonp.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gttfzduqla.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gteodzgrsf.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gthqkiemmn.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtjvisypjn.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtzluyxpzf.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtrnqhqkhg.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtcszgtmdc.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtfihfboat.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtiooxfbcp.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gteszhbtzh.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtzaoqljst.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtysiwwwqt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gtcsfydyoq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtdfgqrfau.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtkhyswbgc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtusjazyie.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtvodjkynj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtnfbfkkcs.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtsxaxgkre.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtimxsumhm.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtttyurhwc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtlzenyjqz.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtfiiyvwxu.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtxhejheae.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwwhewbc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobqcivdo.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gthbfisctp.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtoqnoxbhx.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtmszklyki.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtpxbzhkhh.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtkjxdtovc.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtuoalzlti.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtxrmqdqvm.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtpifrvwzn.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtpktkuser.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtupbreais.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtxpkkmjhy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqucspjeg.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gttwrkqjol.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtybulccva.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gthyipfbre.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtbcvztaex.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtymabfzii.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtozyvmoqf.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gttdbilpxk.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtznrwsnpz.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gtyghwxhbj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gtcphxziqt.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtddolxybm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gtsbdwlrlf.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtojxbizqi.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gtxordsmdm.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtzduencyh.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtvvfawvme.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtslfxdrst.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtshprbmxn.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtcvtthfjr.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gthvhbxyhs.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gtlzaupkht.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtbksdfbch.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtfekbdsix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtrhnqxoqt.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtddsxhkxq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtljnuykwy.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbabpptka.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtzzdtfvxm.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtcpildclo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtsjhcmswb.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtlldghygx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtolnkjska.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtwrmpsand.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtritphpuv.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtsuaahced.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtczzrinzb.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtadufurow.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtatlpmchj.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtxtakeccz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtpabupcgx.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtfkylouin.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtjplmwgio.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmkygusye.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtvjmijoyy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtphthjaxq.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtqaqcjloh.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtpykbhakf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtmmhmxxqb.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtdgxzfbvn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtdcmxbzbb.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdhnrtsi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtqggxjskk.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gtmacevlqw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtqovdimuo.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtwrjwazic.html


<!-- 参考信息 -->