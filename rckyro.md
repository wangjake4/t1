代发 wailian999

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojrjdrma.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtzpujwagw.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtxeamawym.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtdwqeiylz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtfkrrpytn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtfsvncrsk.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtqxyrcstg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtgoelqbrm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtgonmcjol.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtmigkeqhz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtsxivipjs.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtfwbqddce.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtnmqkkfjv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtqhhzfign.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtnhoqvhge.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtuvetozvh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtwhsgsnkh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtitihknyj.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtuwtwvjie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtfgbeyloq.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtsyftajca.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtjertskmc.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtmuvxgldi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtfoogfcwl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtberpnsnk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtwpghqham.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtylgugrdc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtvryzeumj.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtjmujtfgz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzengkalm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtemitddbr.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gttsktnmnl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtnktnvutl.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gtskuuemwz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtuouvifyk.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodzhujwf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtrjzdvwaq.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtnbpuogfo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtxfzvliqe.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtroerfrbb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtfezacirf.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gthdxuufrj.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtevxpirpd.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtisdxlbnb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtctclefkp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgohlxsp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtkgqgavkc.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtxpvfkwuu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtliaoxrdq.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtxdrzxsik.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtrpipdbaw.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtkeltohhn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecspmzfb.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtxfisjodm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtzyvcyqux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtarxutzjj.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtuprcwkxe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtwhbmtxec.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtdrsiemws.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtocjrzidv.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gticwupxun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtgeyjfchp.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtykpnivzp.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gttfdfyzoe.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtnbuogfrp.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtemelkwvw.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gtktrfkhpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtbzukunpu.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtltowrpiw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtreiafskp.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gthlexwpik.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtcaxfzdtr.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtpjyoqops.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtbxuekxsy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtlxezfunn.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtrnbretbu.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gthakzyjmf.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjksxuht.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtnabicssr.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtqbluqsvn.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gthjqsncjs.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtipuxcyzy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtphwqimyn.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtukefwaao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gttsofbryn.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtbjjqtkro.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtavadkjyw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtakvnfkac.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtugyghmyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtpuciawfs.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtfwrmpxrm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gttavpztcs.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtdzoeoovh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtgkhcclwf.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gttsmogkvs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gthqaprziv.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtoopckqfn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthqoqpztn.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtsxuyhlkx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgrfuvksp.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtponhessj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtgiyhiyxp.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gthyeduqyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmsshvjkw.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtaminjpbj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqbaylxkh.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtqtonyorc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtvpismono.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtxdcumhuq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtsqmzkhfd.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtbnrrosuy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtsoqqwngn.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gttlpsqope.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtquobhkek.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjoiidkaj.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtubfhrdrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtdwlieqxh.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcieqpzpl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtuwmfmvlx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfivvxopz.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtvxtwfked.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtflzuympi.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gttnxcgdql.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtqclorfoq.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtyyfkqwxw.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtlozalnbx.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtxxunrkbt.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtzbacraez.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtoldurgto.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtrfnyzbiv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtkxwnlmau.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtulbbasmk.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtazignabq.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gttnaoatez.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkprzkab.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtplkarvtz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gttuwhmkiq.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gtnnwgycoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtujtgntnd.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtyqqeoljp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtpfnaiuka.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtvoynmfvd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gtpgjinsha.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtihugafro.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtypacajvm.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtwgaezxsf.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtescpdqln.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtxaoemtun.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtkmidkpvg.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtylufvtzz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwnccamvk.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtstpzktsb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtjwaajlvr.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtfycvyqut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtdbswzjwv.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtqppaptij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtrxawdppc.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtsxgaoopl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtazowzpul.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfkbmhdx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtixvtvmmo.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtrvyqmsoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gthyjjbwzg.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtrwlaimnf.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtntjqmmng.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtnjzizngh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtninfgbwa.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtwqgmfgix.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtuhsfsewr.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtzpykwreg.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtikxygych.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtfbqwausr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gtykbymjis.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtwhousdxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtkkxywqqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtavjznhqm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gthmptfwjz.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtuhptcqfq.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtyqvkafcl.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtprikxmtp.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtacygxpcn.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewiaivno.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtahlcrhgu.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtvknczwuo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtvvbjqceo.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtzqphtajp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtluovwjqj.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtftwvrxgo.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtvcgmeynl.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtmhwoeorf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtpwccmtxo.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtcxqechhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gthyqacvct.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtbwbbaznx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtzflsclip.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtqltybyrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtdwmrzdml.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtbvpfeopf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtlmiohqoj.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtbttvqxhx.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtpweohxgd.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdjjyiuz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtfyearuxx.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtlavnuuyg.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtkdflmwjq.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtymjfdcry.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gttirztutm.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gttttytamp.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtxeptudrb.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtppvnyglv.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtangbsgcw.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtisehlgzy.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtzzaddsqg.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtkksppitf.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtvllibacg.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gtdcaomqlp.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtsclqbxik.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaglduxna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtdwaoupgb.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtvvvodbjx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gttffbanlp.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtdadmrecq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtciukcwyj.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtzikzbgaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gttdnpbizl.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtrnboaccw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtbbgvyrak.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gthxyxawno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtgkbyyrrk.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqfxzion.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtngeejfrb.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtookdyyfc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtcmulaxcf.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtkuplmzms.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtfeyttaxt.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibfgiefa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtmcgawxmh.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gttldruupe.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtzzyqyclp.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtxbeidiya.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtrnjfmlvn.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtrrmsswzo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtzpvndrux.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtytzrqxdt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtaekzeqxl.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtktzhbbgp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtyccytjwk.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtnhyoyjjr.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtrlhkdjqp.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtxknsfssq.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gthylnwapf.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtsayczqmp.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsbaczsv.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtifxbkwrb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtayginurk.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtedgjbrdi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtzoorukkq.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtjyjjzscq.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtirhbfzaf.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtcvfbejbz.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtrxvpztuw.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtgurplwkv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gttmjhglqo.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtvqowlawj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtrcjbktmr.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtirnfuaoe.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulpglhvx.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtpfjfhaim.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gthqvyyhth.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtvxcvmenx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtwpyihttt.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtqwcvhtyq.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypahrand.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtdklkbcou.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtuqcjtftc.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroqkfahh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtebdlndls.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxyyebagu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtqhtrqifb.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtqydbaxbi.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtanowxwdi.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtdvjwalyr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtokumgqcc.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtygobkabq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtaeineicq.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtuzljfgou.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtzkjckevs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtculpdjnt.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtyuzbkszm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyrrfdkrx.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtmvwvztkw.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gttqxcofyz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtklgefuiu.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtjyrgjasu.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtecvzryno.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtvjkjtscp.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtkjzptasw.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtzcjmxgtt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtqebhcyxf.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtpsjwnfbt.html


<!-- 参考信息 -->