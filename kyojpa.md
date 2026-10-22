代发 wailian999

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2woklrdtj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gt2bnwobdvq.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gt2fpsvsxun.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2looeqina.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2uqywuoqy.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2nplxfeoo.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghiuiffm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2sqgjvxts.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2trdriwrh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2fpjafglq.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkvnkcbm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gt2msvgwhgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2pngtjyxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2lshosjnh.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjcnhpsm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2bypcdmlt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2ecmeuqci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2eduhdrup.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gt2xqwbcyrs.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gt2uhtdfjun.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2rwvennxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2iwmmvubh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2azhtatsq.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2wxhxihxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gt2wlltuqke.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2dycamnbc.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2gnetomga.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gt2ozbiwvfn.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gt2ohagebam.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gt2qacvgtpl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgqlniqk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfkemojq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gt2cijqakwe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2zgexzcqg.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzppnkok.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2bwmwfzpl.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2bdjsavfm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2njghotrk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2ztckhavw.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2paepnfrj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2icllnbtg.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2ibnrjehi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2wzjzizwv.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gt2aovricoo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2elbrhprt.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmrghphm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2ymldhkbb.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gt2ixssxrrg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2bjtvzgff.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gt2uooiqayo.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gt2ndippdee.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gt2prkpldxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2awfxvzde.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gt2uddfornw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2ybldvuch.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2akgzhmgi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djbbzjid.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2tepaajgz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2nfudyexo.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2hhlmawqt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2rzhmkqxa.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssswjbix.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gt2dlahdcwo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2qftvndto.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gt2pfztgmxs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypcfxhby.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2uhlawjlx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2xkkxxzps.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gt2cctjefzw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2hhgcpooi.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gt2jqukifif.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2qhwpybrz.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2rbrqotoj.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2captactb.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2iagfdkje.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2slyzgmuq.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2cozhjaov.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gt2nwhxxgbb.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gt2hvbmwfel.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2hwcduzeq.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gt2uopdykpm.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gt2ccklleau.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gt2nirpvdsk.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2riletqiw.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2dnbmpvem.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gt2nwgjwgqi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2eagynvsq.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gt2xhbvwpnk.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gt2jyywkitj.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gt2anluxliz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etvdaxpl.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2xkqcxrdi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2uaujfybu.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2svrnmrjx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2uavykdva.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2jwjprvfw.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2lxbflnjx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2eihnxfyv.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gt2imkstwnm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gt2ehdjuewo.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndfefxzf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gt2nmrzcjwi.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2oqbjwroo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2ccadcarv.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfgqrlcm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2tfmgtkuu.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2nrxrjqjm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ablevmbs.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gt2kiutljyb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2jwkcinph.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2wiqpdpsj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2frtrseiv.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2ftkjqpvw.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2knqefznu.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2pwssqiqx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gt2gvamacuj.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2bpjraebg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2tsncgxqh.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2thczqsfy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrynfgwb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwjouawx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gt2pbltyycj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vxistsfd.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2wpnqwcex.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2cprtpjvc.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gt2htkegoyy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2mcwpebsm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hynmhscq.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gt2fjrxqlop.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2wolpnnaz.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2uqqaeaug.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2icxxplgq.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gt2broqhfxs.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnsnunjg.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2hikiggky.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ptobgvwi.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gt2ypquvvhq.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2jwsrzkxl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2nrbyricf.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gt2raufszfo.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2hsjgdzzb.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmaqwhhf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2iairydqm.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gt2fyjxztve.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2vlqbigmy.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gt2fptdoebc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2ljazxhqh.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2cfsmotof.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2wmbvtxzl.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2gvsdyrcp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2pywqygpf.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gt2wlmmygjt.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjsgbden.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2jqitfnxp.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2xluxoohd.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2nalsxyja.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2bfrykoqu.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gt2jxwnhvwk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2pkrcwggz.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2ijprrejb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2gjowfyml.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2uooerlxl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvjqadjb.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2nftmbfrh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ibhvgdbe.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2inbqdmbh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehugbmsl.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gt2coyzlywb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gt2jczhhyva.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2hjhwglbq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2mwhhytbi.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2mbfxwxib.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2dndxolda.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2apxigakr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2snufsbzx.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2fvtikqpc.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2zmawzmfy.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2ceyozdjc.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2ietksxdq.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2wartbwie.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2jtenxdsd.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2bjczdnan.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2fkhdsjvn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gt2socjtijk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehczgjlt.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkilodwa.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcurjuhb.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gt2rggjdytp.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2icwxhbct.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwgdmgyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2njdaawlq.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2eueoyjku.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2cstczocm.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2ivvakvpn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbjzybgc.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2valscmqt.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gt2hijozjqe.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gt2gatlhfnu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2mrkyjuor.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gt2iyrtxycd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2kdnvwaze.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2sdvvzjhj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stffnlai.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2fnxixpxe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2ztrqgxky.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2jnkvoxyp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gt2jmyjxzxv.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2cwuioxec.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2tlekwgzx.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gt2hyyjktzp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2vdiplrnw.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gt2iekpenjb.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2maxujwjp.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztybnzaj.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gt2lpylzuqi.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymkounob.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2gvxpfqhm.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2hzngyajk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdtgyya.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gt2hgdwlfbv.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gt2mikrelnx.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwptpwyb.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2cwewgxug.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gt2evezalxp.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2mfckdqpp.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2tneuexlu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gt2vkjnkagr.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2nwziiziu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2gslgtapy.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gt2kpehoefh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2xdeglsuq.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2liyxvakg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gt2uztliueg.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gt2jobbuetb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2uzyisuun.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcaaqoqe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzxnbqz.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gt2tqidpfsa.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnfqjdnu.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gt2ahupxdub.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2lzmejxda.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2clnikbse.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gt2shsykmiu.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2lqvfpeyy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2cokioved.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2lygzrlhc.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2yggafjvm.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gt2gpvsdqzd.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2wzhfypxh.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2oumsskin.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2bsysqaym.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2lyplvenj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2bummkuwi.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2ktwdcbuj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhakqswi.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2vuxmnlrx.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyaijjyo.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gt2vnaujpsy.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gt2fezqkcmj.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2pfxxncef.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2zavjnxle.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gt2lqqiumyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gt2ajrpswzo.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2ipftpiew.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eteeahcb.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gipvbfps.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2dtwmsany.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxochkvf.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2ljroozcr.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gt2xazrvzea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2uoduvqkk.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gt2jrnlptbz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2ldzatxag.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gt2qepycaoy.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2rlpdmvts.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2conofaaw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gt2ohwcusnf.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2basbnyzw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhragzrq.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gt2bsaqbvaa.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2bkherruw.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqpmwhyk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gt2zgyofmlg.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gt2jfhrynhi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2aycwjtac.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gt2krpjvick.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2ebyzdhnb.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2ohbjkceq.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gt2iknwxijv.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2iqvcgrdb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gt2eytjeuwu.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2neimrdns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2zhqhoeof.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gt2rxpqtkwq.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2oophkzfa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2prtzrtuk.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gt2yxkflywf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zghvhzjo.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2mvahavib.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2yhvwqwtg.html


<!-- 参考信息 -->