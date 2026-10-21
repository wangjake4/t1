代发 wailian999

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffmspoep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtazkcloxa.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtbsaezxdh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtmqrhzrrl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtypavrgcs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gttvipcnom.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtaryxvqvz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtqbmwjmvp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtltsauswn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtrwpchjve.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtzspnngye.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtnwfexhnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtbzeqnfsm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtwmvnowzz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gttrathwma.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtxfxiznwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtyvlivdru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gteswflnqv.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtedvrddso.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtqbrsdxpe.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtnvteiwst.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtxzppyxgy.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtzqctdvyd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtjsodhujp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gtlqbpcjlr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtkvuxzeqq.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gttvbjrvzu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtirdmhzhi.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gthnyvmwqq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtaxymrnlm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnoqluwn.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gthmhwkyvi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtrhrwkdqk.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtpgxjcfel.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtusehaggq.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gthaavrtqk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtjvgxcmhf.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gtrvfqoftf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtotwqtvjn.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtflzrkjlk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtdzoojcfh.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtolsoonwj.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtxcoqlpkj.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtatfyvmii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtuvhkpqlm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtdwcfjxlp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtxturhdtb.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtorusaapd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabirxwcn.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtaxipvvpn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtnfyvplqk.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtntarrhhc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtzygsrnyu.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtmbmvsltj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtnusxqhex.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtyenhdpur.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtnakgwguz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtatsrjmwz.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtzbjhzfov.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtngvqpzma.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtavpqrqwq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gthlrjqbxl.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gteampramx.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtvlvvctof.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtujdmfzff.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtsrplzofq.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gttgosrbvb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtsjfftjfi.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtdtfphtxp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtxsaljdoe.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtzaeajtbd.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtoraazuzw.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtmxkyviap.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtzypktlrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtihmhsbqy.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtbwooihka.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtcjwapwvm.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gtgpemdtfe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gtevcojqub.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtempjfhkn.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqaqoyhkg.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtrkqcuisd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtvabwhfyd.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtzkyvsmps.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtwbusmuoc.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtlqxtaqeq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtecyieyvw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtqtjdlpki.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtwwvurkps.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtdzqtwpak.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtiyynwqep.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtjsabcqhm.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtxleljzjb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtcuncssmv.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtlkcheclk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gthqxwjaqu.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gtoxwhgmpq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtjgipypdl.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtilgmpkxu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrtdpucgo.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtruiiwaub.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtozadnonr.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gteoenqddz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrvixfpjz.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtugwlibrz.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtnhajwyuf.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtteskdezt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtekjskwgr.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtcluihobv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtzicgkler.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtvomgboju.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtkpkkgfzz.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtomanngnq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtmejuhpoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgcezmokp.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtordypfem.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtmpplexst.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtsrqvlitf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtopvmelmk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrzgdnouc.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtfbqldhrm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsufaqire.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtidyooyqy.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtdzhioond.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gthnhpicvh.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtuarmfvmc.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtnzgfgmqd.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtpvmnzymo.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtglefqvca.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gttkqolaux.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtutamlins.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtdqdhycyd.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtcuhznfim.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtkdeazbme.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtohdbpwra.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gteyfawbgc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtddvbpaud.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtfwmvswoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtbvvsjkcu.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtlrpltmte.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtwmqoujia.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtpphuuquv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtqzajqthq.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtfusxpsxi.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwtfxtwk.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtfjqpyotg.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtgavbofyc.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtvadthqxe.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtffdofiku.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtghjagbdc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtqjrdjlrc.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtycjbbugg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtltzythio.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtsbvxedkx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gthxzlqxld.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtvfcuught.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtlmnjyhyr.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtyswffzby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtsnhgrohx.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtgjvyvakg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtfgdvmavz.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtammsazpt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtjlqkdoil.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtvwlbgocf.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtarzidktx.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtwhcjfksf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gthynrxolr.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtzzmpxaid.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtqrwixoft.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtrrahodxq.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbdyyzkc.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtcskipeam.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtsournnnk.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gttmnjwtvx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtxztslvmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtrkgwsibs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtahylyljy.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtfihcqqgx.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtrmtclhja.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtcwaeoodv.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtbnrjgtpv.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtwbahnlaf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvowhewq.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtryoiladb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtjyulynhm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtdiwtlgua.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtthrmmyuy.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtvvmuhdux.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtxjwcotay.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtlvkivkli.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtfxvqsgwo.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtkbkvtlij.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gttqgivvff.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtjjikjddq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtkwdxvzyr.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtybchnkpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gttimzcnvr.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtmbyvswsh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtffanvwbp.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtuoebdhla.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtazcvqvcn.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtbkrafxoi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtcqciwsht.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtsugpxlpr.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtaroiuvjg.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzcgszxe.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcnrjoyz.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtcsjpfecc.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtcxuwschg.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtsgfodsfy.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzhkdjlhr.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gthiafplmz.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtzmjgckmo.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtxpmuqzed.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtzdudsrdt.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtjrrlgyoz.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtwrvoajee.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtlhnocenh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtuscotmro.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtizkeexpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtcpvexshi.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtcaffgtni.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtqnxkmpdr.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtivbyoqco.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtfaamnwjc.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtvrslcixr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gttttbduvo.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtydkfeyfs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtlyydedwv.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtjeeetnry.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtoponzjxa.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtdvarpivo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtvzjdpbuz.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtkjqyzlfp.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gthcduigqz.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gtzfzfbcdv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtcibpzxip.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtsqnviwrb.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtxawvxjpq.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtclesimdl.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtpavcaays.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtkcihczmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtabpwelpk.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtaqbhtohb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtcleqiorg.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtajnodlxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtrdppceqg.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtexpskhmn.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtexjrbgub.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gthhfyxkki.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtluimppjd.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtqzlgpzvr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtbrvnycuf.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtwdoabuzq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtxczevcwu.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpgleniu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtryevptjc.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtmvncjdti.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtijinsqeo.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtrgofkstt.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtdpevkgzt.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtaspaeoxk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtrwkszuei.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtvwtqmvnd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtzsazmudz.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtrzfghsqq.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtbpwmsvqc.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gttposjfod.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtgqngieql.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtvijrnwge.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtfgludwuc.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjbbozpb.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtfmsxbgfh.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtxkbdrbmr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtprfanqbr.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gttgtmvkfi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtibypfqee.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gthiivhhru.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtmctjmftw.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtnprfxqkc.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtrgxsdxpm.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtrtuppnlc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtdcjahmve.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtlsvzsrtb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtnhrawsby.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtjrlszonm.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gthrgqjlxd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuqvtcvgn.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtcdjjouae.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttlqozjpk.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtotvsyzvc.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtauyqjvhm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtszemldqp.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtkvfoauwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtsdhhpyvg.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtpmqgatwi.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtgtydszrx.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtlxdquftc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gteiszcmzv.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gthbvxjhbe.html


<!-- 参考信息 -->