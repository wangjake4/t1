代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gt2zoyrrxju.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2xuoxpkyg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2swqblrcr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2yxghoipl.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gt2mzfpwpez.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2eibhurhf.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okwrouoi.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gt2wuubvgmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gt2nvmzuviv.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2rvsqusiv.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gt2hntqtsve.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxwownvf.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gt2irkabmyn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2wvbilnhe.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2ppkqcaui.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uizwingh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmwtxcus.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfxhkora.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wutbeaan.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2znydovwl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfssliri.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gt2ghzypxta.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gt2yctnacmh.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmnxghvp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gt2fqkxvrob.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2dbdweaqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gt2xiupzicc.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2vaxpjpzq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2qzmtwiiq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgrcjspo.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2gdmingpo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2chetiscb.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2prlupvpi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2ysaftyfc.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2wndeqzoo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2hfvbekcw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gt2ndexsngf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2janflash.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gt2hepbvdhl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2ewdkdhae.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2lyzomcvu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gt2kcloojme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2wzpxgtet.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gt2ehqbqgge.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2afhaohjy.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gt2soybnlzj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2ruukonkl.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gt2kasezaye.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gt2jxzwjtnh.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gt2grabmqju.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozaozpfh.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vryoettq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2akuskkeb.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gt2ogfngrjg.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gt2ynllbdci.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2vkiuashq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2tceggkhw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2trlhsxxa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2ngqgbspd.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2scrmnfhr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhmashcp.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2ysqpavho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2vspmxnki.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gt2josfowcj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2foeceooq.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2qchtculn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gt2kqbakwum.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2pwkyhdkm.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2nlkibjhh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2gslailog.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gt2nmjmcqcr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2gijzoclx.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2mkecydsc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gt2gltzhvdr.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2nwantikz.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gt2vtkqdajh.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrcxdjwq.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gt2tlniylbu.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2oaezbnus.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywjjonoe.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcwxnnon.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2zzzwnqxy.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2aszjxxvx.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gt2tcfmxoce.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmsghdlb.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2kwwdfidr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnuofvye.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwuwxfvt.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gt2klylxhff.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbbaubbt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjeudrfi.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2uchxgjrd.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2ttkpgeld.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evmgpnxg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgpvcuur.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gt2uucjyypl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyxutkau.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2hswqbtum.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2ngjukhxv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrlaagws.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gt2wbafcleo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctnpqxny.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2uvzelvci.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2xhftmibu.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2vhpmevoq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2tvrjdjth.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xttbvyyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gt2gswcxcuy.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gt2dnznutgh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flgeluli.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2rlypnbwu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2piyiqkgx.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2zoyjmvvy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2augjyklq.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2ywqkroae.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2aezeadju.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2rfljwytt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ujtowtve.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2ryatgjdj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gt2yflzvbsh.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gt2lrihagzc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2ckuotyzv.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2addumiiq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2cozpsite.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2jgxhawpl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gt2btgufitt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2izfxykmf.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2htvarqyc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2lklqzssa.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gt2ldqhjafb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gt2knmjzsnk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lthlxizi.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2sncmdess.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2bawnnudc.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2fupddewa.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2arrxsflo.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2jsdqpenp.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnprqchf.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gt2qlbkvnob.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gt2vapveijy.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2dvgiefxy.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2hvbbczrx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2mlxxcrhb.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gt2dnkraalm.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gt2vacxbhbp.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2ynfooclz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2clnymivm.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2rvlwlnfb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujihvjao.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gt2huknewvs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gt2eroydpiw.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2zkmmtbpt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2tejnpnpc.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2swswaoza.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2yhpgfujp.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2tykuhzvd.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2kuyramju.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2ujncahue.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2jkbogelv.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2htgdzjxj.html

esac
来源：http://dali.yonumen.top/Article/details/gt2zftgxuqb.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2gdlbwmke.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2haiafeyr.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2vjfbvmtr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2kdawqfnq.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2fnjjhmgw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2crgxkowm.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2rgrwyiax.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gt2xtoeewxw.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2nmkqobrf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ncfcnpeb.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gt2gzaiuagq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2acgawpxy.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2oduubkzo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2yzrbqmeh.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2bxqmuktk.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2vloumqru.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gt2vldixfvh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tssisrmq.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2npihbmal.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gt2rezgpzll.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2vhuyhfez.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gt2pczcouzl.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2yqheuqga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2ceexowea.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2tlzlfqak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gt2ktvvdave.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2upmwnqdq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2okbwuryv.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gt2ezoxdkqq.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2hcxluxoz.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2btocdkcj.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzxclfbf.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2wpkqfugq.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gt2plkrrtvu.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2rfqdsvgu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2thvfmkqe.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gt2qrwfbsmr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2dezjphxl.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2kieelzfo.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ezezqbij.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2tlkmtqwu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onzipjla.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2vwsenrhc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2spcufvll.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gt2aafqiqbc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2xuknlbwo.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gt2nzlqrmsa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2tbwkkdez.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lujsddzt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2bqlbggpl.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gt2jscudpay.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2wlhdznsk.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2vktutvwm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgxnqonx.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2aztkfsnm.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2oysdkahh.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2innorhhc.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kanpuitc.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gt2ykgkozyg.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2fyfdrkns.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2muiegoqf.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2yaeimwiu.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2atvfaots.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gt2wkmzetbe.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gt2lghwbjny.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2ggugxcvr.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gt2kaxiiawk.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2bhwuolpf.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2pufebhny.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2kukqjfvi.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gt2vhwxnlaq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2yhodngup.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2nsrjgyvl.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2nciijlle.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2xqjtnako.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gt2crydqhii.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2xoqhwqio.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2apyenhia.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2wmaxcqeg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2ukjynlby.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2evtultxg.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2mqdiehcx.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2whfhonkw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2tijrkmfi.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gt2mppewqry.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2oxvymrpf.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gt2emeagsvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djdcpewo.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2zjvkigph.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gt2ycipjwpb.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmylcrcy.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gt2ynsctbfo.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2xocqxvpg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2oxrqwggn.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2svrafbrt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfmbpxeh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2ovqfrwxq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2ydttbpam.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gt2kleehfnn.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cghiiewy.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2dxmcmuke.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcxsmtyz.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2oktjtejn.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gt2uhisfmti.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gt2iknfybqz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2vndrmxrt.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gt2umobuenr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcqoopep.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2urczyxuw.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gt2lcrxhdjd.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2xfqkaphd.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2gzcsipxz.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2khkmelqx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqhqpnvl.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gt2svdjyigq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gt2stnfejmp.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2agrshkvi.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2hkmlivym.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2ldvggtvw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxnaizbl.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2vakxitsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2ngmibugv.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gt2siyogusx.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gt2ccseodee.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2gkfbwhpt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgcwnyws.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2zazwccvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gt2pznzwala.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gt2bwlfhhqy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2zegslxni.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwtdmfur.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gt2crtpobst.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2nfudcufh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gt2xnlbyfpe.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2iarkshxn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkxpaosp.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2nwyccgdm.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gt2hotckavf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlgkqswi.html


<!-- 参考信息 -->