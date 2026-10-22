代发 wailian999

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtjwzffndt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtlrtxkqou.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtdxdhpfhu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtgdryovkt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gttehkcgms.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtigiloats.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtjhbpvglp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtgwpfhyms.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtqvmsprhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtiojhnepi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtsfromyns.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtfpliakce.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtjwtexxlw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtqqublixl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtobutipcu.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtlhvufzkx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gtfqwqvobt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtepscojpt.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtfljhjprz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtwmtbcfcy.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gttjmllkme.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtmviskxro.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtddenqjpa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtsjgugjgg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gttzmsfafz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtrtcxjrvw.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtmdpzrmet.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtrzjpochj.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtpfivnazs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gttcekqosf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtesufjdjx.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtoudekfij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtqdndqnyw.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtthgodsxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtgcacinzl.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtiezwewva.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtnhpufrhp.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtuxxgajwq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtaipveyub.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtrdxfbcrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtsxbtrudw.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtdxrdjvxk.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtjortiahl.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gthjawsskf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtbfzszotp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtokuzybzu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtihgbhyki.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtzpglheea.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtbahcoqwl.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtdqsecsdr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtvupxcpld.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtquyrbumb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtiwpgciqh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtfqdvbmrt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtovkeeeez.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtozfsvknz.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkulbusf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtiqbrmwig.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtkujshhis.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtdoogppmb.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtrbolkivh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtbgpljdbu.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtmblvaucz.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtfwiofery.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtwkltyurq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtpbqilqsg.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtlwifbtle.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtyyrktqrx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtrcqcjeru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtlislrmob.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtgtamckmn.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gthhiekexl.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gttcuzezby.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtxyityapy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnzlridq.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gtkyjalzxk.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtfrzaxjpi.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtmrahvcdu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtsxxjphxy.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmvgbswu.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtmnshogty.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gttukmggpr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtskbtfnll.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gtmichzpji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gtijyhfktg.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtdmprrmde.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtxoqnhqub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtnluzffxg.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtsqvhwadd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtbarjighc.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtpeqwgafw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooomwkzp.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtfictpaig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtlbpmlkol.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtklsjevsp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtikpatpvc.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtnscqdgnp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdcdjywkk.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtcnwwdcrb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttzzaurbl.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtquxyyxlw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtauqtibzv.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtsdmoapxb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtsdxgujdw.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtzboabyxz.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtjshgovkg.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtvitlveup.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtddnkbvlu.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtkfggqblv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtuibjyvvl.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtltlyuflz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtcrnagitp.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtdglaluwy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtrppjgyim.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtikgxdbrp.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtfgdxbrqy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gthcavewyb.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gthrxgspoz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtjedcnwkn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzntmqvij.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtwqjzxjlk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvetojidd.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtcclghjwm.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gthkqbqtrx.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjpmgqte.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtrosxodda.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtthzshfvb.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtubrdnvqr.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtujqvdnug.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtkjgpthyv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtwzurmuwo.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtrxwrokga.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtpanmnjqu.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtctevqlfc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtnisjcrdb.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtokpxedrs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtcbzefmvg.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtdoatmfps.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gttvsybttz.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gthlnufyll.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtgprsnlsg.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtmqxgduln.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtdswbveuw.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzwnxgaz.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtkdeyzghr.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtahseyibz.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtjajrmnmx.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxtthukc.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtirowkczd.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtaqmwezpj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtwkyggmwm.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrknnpfy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtogtloyor.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gttwigzvye.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtoxetsdle.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtsbnkkljo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtnofbfabe.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtfsknezjx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtrylrdflp.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtdotywckp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtyyujjkah.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcygsyqd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtdgevohwn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtrkhxaxhp.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtdlcpiwwp.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gthztfhjbx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtaeirbzmm.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtlwdibfpp.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtbrxuajpf.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtcuiokvjw.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtilhawbzz.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtnhedwifh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtoaylvwho.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtgzrzajiw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtdrrirbha.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtteplwjte.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtjqxyeqwx.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtjdizaumz.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtjizvvdwf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtuoplnswk.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtsjzcjieg.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtdbnlvbjb.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtogrtpbjr.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtxnkynefc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtdonspysr.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtkqysrxvs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtzxyqzhqc.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtdbzwahgd.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrejsiqgc.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtswhemkxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtfyeyorsi.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtcjzlsvpl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtisplnthm.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtgerxclor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtngavtxip.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gttwbbauxm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtxpboqcka.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtsevukvkf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtxcmewywh.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtzplnphuj.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtsrrfiina.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gtbbkjuimz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtsrdcnxao.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtzhmxonvq.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtqrbeewts.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gthqanohui.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehcvufgz.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtklwpqiil.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtoixoclrj.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gthaaouode.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtnnhatmfy.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlzfvyopn.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtawkdykel.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtingrlszk.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtwrvqko.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtqnemmhhr.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtbxloewqz.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtefotbati.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtnyphohso.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtkskvqrru.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtamglzysf.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtadhrxhse.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtdcmgbydo.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwcmcoog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtczyweimg.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtbrhrdjoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtpuhaxvng.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtgulgjrte.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtfdcpkbko.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzqrqiex.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtixypaefk.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gteujbcsyq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtlpuleohl.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtvwbpiejf.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtfucamzej.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtbbzunnop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtqgaftmej.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtfnmdnuol.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtygcmpdxv.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtddwnthlw.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtexfveqft.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtfcamucrm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtyiltxdfm.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtazxdgktw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtjhcxbzrf.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtnpygpjyp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtqyssudcf.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtcoqmppxk.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtutsumkkb.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtcgykueln.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtqzsdgmlo.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtgbqufffl.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtfmvnvnpy.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtitqhtqph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gtrlwghnib.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtwdhonlln.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtzmlsgqyr.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtouzklhgo.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtetcrxzli.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtzmxkmmat.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtbttjrzvk.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtfpydpqto.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtdatzgsxv.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtdycdspyw.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtzedgdnmg.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtrwnxlimx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtbjouzjwv.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtpzkifqiy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtqvpsnhrg.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtytksiqfr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtiqxmyfae.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtooxlwdvo.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtuhccyanj.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzlsiiqe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtdtmcvnoj.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtrdhknjrj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtvjdxvlzn.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtnoxsolkk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtbszzspgf.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtwnvrulln.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtoosfxjvg.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtxddxympj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtywzledsx.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtbiallrev.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gtykgmpvuj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtqbbklgoa.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gthepepcsv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtiqhpvmuc.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtahqvmdbm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmkmdospx.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtwfeexmyf.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtktaarxbn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteizwehyj.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtiamqradg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtxwxvafdb.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtaimpzoeg.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtjhkfkcca.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtakpyathl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gthmbrxxcb.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtzjibamst.html


<!-- 参考信息 -->