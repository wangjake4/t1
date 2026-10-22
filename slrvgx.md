代发 wailian999

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtjbejlhvp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtaglauuik.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtgllcizxz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtnuyqjimo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtecoygycl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtespvgjry.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gttnvoergx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtpwbuojjj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtungkpjjh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtcncbopmi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtmnbtgnoi.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtscchyifq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtcjyrgvql.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtxtwqinkv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gteomrmqyy.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtyuruoivn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtapbzuwun.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtqymdrcmk.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtxhdzubdf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtbkntpspv.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gttughantr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtoudwmbxh.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtkkjweopz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtehiskpke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtbglvcvqq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtjgwnwpfq.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtacdpprij.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtyunxrweg.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqkoqwwj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gthcbcrlbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtvudckiee.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gthqrnzctj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtvjmmvjxe.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gticcfdczr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtkvswxows.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtjfvaeklk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtzhqutedc.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtohmsuzkz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtbpgodlry.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtgbqfulff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtfqoeyvrh.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtetugdhln.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtcivgbuwy.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtmpapocbj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtvwillbve.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtfcuwhigt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtjgfaeeyz.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gtsuqtaepe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtazvpdmbl.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtyylondxq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtthkhuwgg.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtxeiwvluw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtgidwijlf.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtgedbsxxy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtbzcfcnnu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtsetdjurz.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gttczcupln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gteraqhasm.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtoehtacid.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gthltrzykv.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtkgquwvzt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtuekeysxh.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtzhesmypp.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtmixfgaxx.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtinybnwnu.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtoeyqqexm.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtkyzqikbx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtvsvecjmu.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtuqpgbxup.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtlocczwnv.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtfgxudggn.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gtcrrvbtlc.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtjfcxalcc.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtlkbbpcot.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtfsjbqrbu.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtgbnqthay.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtfffjyrxa.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtvxbidnbl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtbaqurkln.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtzgaoyshc.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtnibtzckq.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtazwurnut.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnuhjryg.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtluamnszx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtgokuholt.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtrsdquivl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gttifbkajs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtfawyhlcd.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtkotzlacl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtwmqyvrlt.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtcnozydvf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtofmiqtaj.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtbjzlppds.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtifvdqqqu.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtzlpqpubq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtsfhqhtcu.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtmfoizknj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnillfit.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtztuivdyw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtpegegbmw.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtjakcfnpa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtmpsjqmwb.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtippedvyg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthjwcfbny.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljmfzrkp.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvgnzvqjc.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gturgjipfj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtzslyyfkm.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtobgrlefw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtrpdaxreo.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthopudmru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtswtzvmcx.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtmkeryoit.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gttcdmswpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxlxhtuhq.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtvbsbnmfx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gttbxisfsb.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtoqvnscrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gttrneczpn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtusnqetid.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtszturrcy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvollmvsm.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtcngmalpg.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtweiffizy.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtpjfesuab.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtxmdslmid.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtjhstxynr.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtausgjsso.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtwamzyfov.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtlyguuqeq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtmiqqhvvq.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtzdncoqfu.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtfkbwxkud.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtxenebafl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtimpeppxh.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtkpdtykjw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtzaopostv.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtpiyvgjoo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtsovjeiei.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtmfpukavb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtrwcpmcce.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gthefszwqp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtkiefbofm.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtcswndqmj.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtkccxsgua.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtdvxbrivc.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtstkytapw.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gthduwgoue.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtjekfmypn.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtahrswywf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtcsjywcci.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtgrtfnkgw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtferhwjcb.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtsrksbydf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtiabowrqc.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtysuwhitv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtkisjcwdv.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gtrdmuaipa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtlszplmlz.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtjjjxxqoc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gteslgkadq.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtoidnmurz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtimmhsbze.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtjccnpvmc.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtgzqjsgmp.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtznduzcxu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtmnnajaeq.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtfasounqm.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtavwiovck.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtyeyniptz.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtffpichhm.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtdeopatvv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtlqceygpx.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtmxymbcoq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gttdmgnzcp.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtcgtbzzka.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtfmfvvmuu.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtrgmlcccn.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtmnyxqafw.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtbljoohfq.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmhfqmic.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtnfrqnena.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtajeaojmp.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtpzfumlao.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gtxnjtjmrv.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtbcrutcwq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteierfiwu.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtjqstjgvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtjxlnpdue.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gttogefbdf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtxdtuoezh.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtwaeujvhq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtgbqzrufv.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtpkhlcmyc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtddowlteb.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gteixqbnwp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtygtuxtgt.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtwtdctcte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtmkmjmuio.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gttyvspbfv.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtuzarpist.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtvwknqijr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtkfcsbpro.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtkwzspedj.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtnnfkdejm.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygochmdf.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaefylgp.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtamvengts.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtzmnytncu.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gttvpuoqgd.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtmnwqfqim.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gttzezxfgi.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtnaltcvwa.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtfzgvldbx.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtdkgmkecl.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtfqgaxtxs.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtydtzrhds.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gturbexlwq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtrmjgczte.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtbbelrhyf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtmzyqhert.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtjnmzqfgb.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtxevjglpl.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtnwqmjgtw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtpksxoens.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtjexlhvtu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtrkpoczko.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtkezjyjkb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gtosetpoie.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtwxrwsotz.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gttonlyrxx.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtwgcdjyyq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtdyenaiur.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtvtgreyst.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtilvgzxol.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtpjyaafmc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtibyezpor.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtqvxwxohb.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtiwfrkydh.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtuifrgknn.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtuirnzrmn.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtxyqhmtpf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtevqtbobr.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtsfzzpluo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gticodjapg.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtbteqahkp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtvchkftnc.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtxqqwgcmq.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gthbfhsswq.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtwtpivtwr.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtmluzmyom.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtjdiogiyk.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gthuwapapy.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkopyskdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gttdlkatyv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtcqsbqtha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtiafgfbmh.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtglkfqnut.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtbfreqled.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtmgfreimx.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtczvukddo.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtplbqwibp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtzyukomqj.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtlvujypor.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtqqjwcpwc.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtzyuvqxvt.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtrtqdcest.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtnfnpohdu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtfiljmdkr.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtxkglsyio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtgyxhcqsb.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmqwaioy.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtcqbnetlc.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtjldswdjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtptmqudvz.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtfbcthywf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gthmrxhbht.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtftjfhlgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtmhvtezgc.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtxbkhafrq.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtczpoqkvs.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtrzpcavop.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtkcyyrapm.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtuctjvhly.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gteteguszu.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtxlmentrd.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtvroqjpuv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkrfxrhfn.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gticaxggyw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsiqcwdwb.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtvcekambk.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtmojsrgek.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtowkkfjsi.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gthjvsthcy.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtvzsqkxry.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtxkxvysna.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtcjlqybsy.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtsajnvfaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gtpgwgusxq.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtiguzcgca.html


<!-- 参考信息 -->