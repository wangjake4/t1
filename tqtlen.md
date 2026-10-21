代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtlmdxpcul.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtnddgwvra.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtptdmtlzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtvwlwiqmj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtmiubdtzo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gthblwntmd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtsmttkyvt.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtfceabmnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtjhzylmen.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtsgpsrtpy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtegalitkb.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnsmjpdm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtryfhcioz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtjuvpmbny.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtbrxbetqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmnfcwyx.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtdckbprle.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gttxmledyy.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gteusfaucj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtinybodek.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtvbbtefik.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtkmqmauth.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtbcfwduui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtbkxflibk.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtshexqmez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtkvonfrmt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoegeriq.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gthrpzzqdn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtqoqvvfkp.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtuyfxokqc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtomozpvzb.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtlatybkef.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gteaobszxr.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtcgiccnzx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtjbuxmhnr.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtoycbeoov.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtwptzpkxn.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtvhbcgmhk.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtnqvszfsp.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtykpyncbh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtdayvmbvs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtweejpssz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtmooijlmq.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtktuyamvh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtsdotkmxf.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtslseozzw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtfqblmmge.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtgeeowxdu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtairukxzk.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtctoivyil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtixncjxog.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtfbcqvwbd.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtphurkwhk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtymklmhfr.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtqbzwzfcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtnahjtkst.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtdouyfdil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtkvndubre.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtyokldabg.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtaasposue.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusqtetws.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtimvgeijb.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtigecpuwg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtwtvgifmk.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtkatdergj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtsaibslkg.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gtmtnqfluv.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtbhprbjfg.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtfmoyolce.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtmehjwhdq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtdkoqxesf.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gtslygpsfr.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtkrowswvt.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gteynzyayy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtmgwkziou.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtlfmkfjxs.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfgroqign.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtyahiuzgg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtznmfensz.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtpnmanaer.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtbjxvpdcn.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtkqoftwdo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gttrmgsxnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtdneruchh.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gthyqgysmy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtepfezzeu.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtsieeuvyi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfgpffjq.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtfuognbgi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtesyhtuur.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjfscuub.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtzsistdtz.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtiwjsihzo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtixlhknzm.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtunbkfuov.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtbsvxvbwv.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtgegzvqaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqquazsnp.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgdcsmng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtsaesiwwh.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtbzeycphr.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtooqhimyp.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtcdeuyzmi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtqeuewcxw.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtasmcogpe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtsavqipye.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtbsfyfsjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gtvhwimljt.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjrphmdw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtmcqpeckw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtoacrlffr.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtavweoklj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtoxdjtgbc.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtudoadngc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtbnkdyfgi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwzedctnw.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtxmnpdgjx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgedrgztb.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmbidwoo.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtvmzggzjo.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtgssfzfis.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtfajafqjc.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtmbppiict.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtvpdxqqzq.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtimbriqwv.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtoqygxvnz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtmreikdpr.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtlumienno.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtqbncsvna.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtycemvyuj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtkttigpyp.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtcnymclyz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gthaebknzp.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gthqjsrmcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtoswgrelw.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gttlqffxhu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtojgazrkt.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtbbshtnon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtxwykbakp.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtveoiakxl.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtlbryidxq.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtepduwyqt.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtgvfpbclf.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtlfkvczuz.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtteanatab.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtyfwmictd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gthrubdwsr.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtycoypulo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gttdkokmed.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtzysvpdxq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtlahbftou.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzpqmhzu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtbultfkwj.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtndbxiphk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvxoelot.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtcdaxfxjo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtsxuxfjjg.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtthbfacvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtvsqqnwpz.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtyfauhfkn.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtdfvfcaap.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtmjtrrpqq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtwwhysrwu.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtyqqhbfqg.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtymvvzibs.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtmevytzuw.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtesnodnbb.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtgjxctvlo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtzjkwuauf.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtqwnxapka.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtkpdnljnf.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtpzyapmnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtwctzrlyd.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtnuhpxlsw.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtosppkndv.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtcbonvsov.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtlplswawh.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtuzjftzvo.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtleaihagu.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtckxmkvci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gttgunidhu.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtfamwpfct.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtsbvgaabq.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gthfupooxh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gthdsthoex.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gttedexuwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkhkncbzt.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtspfxwgnb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtfjklhoqr.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtsfkjoezv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtrrrtolwp.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gthwcyiclp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtjqblntll.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtnelyuhhf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtgvsmaliw.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtpfeyhcew.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtitfaadoz.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtkhrbhtri.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtdsbmnspq.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtenmzdbyi.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtnuzonffp.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtchkorylj.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtryzbyupp.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtdcxvpofn.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtoxzywhlc.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtvuabguef.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxhkoszwp.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtlebozyif.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtkiqbzdrw.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtczujxuej.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtqacucmlv.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtruhlbopa.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodqmsypa.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtnnsefzba.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtbdtmbwnn.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtdpgmuemt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtidpogdrn.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsjuvhlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtuivpytta.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtibiawcze.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtcoghjann.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtnhrwvkvb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtcrncwjqe.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtqlynroll.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtkpirrhjt.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtnaffpbeg.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtvupvomqk.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtshltrryz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtcgzqvwhh.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtceyxangd.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtjhnkekdd.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtumldhvvt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemlohhhy.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gttelhlcwx.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gthdwinqjd.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtcyfolojh.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtbsaoibcn.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gthntmbhvs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtpgjaqstr.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtlgsvwjqj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtfrrtputs.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtaecswjdo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtfmmngsbk.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtetbcemxw.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtfgrivwux.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtuqizjidj.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtjwbtijdy.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtccvwhtcw.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtyqrlaskf.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtqczticfa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtvdsyqfqc.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gtbjkpipvz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtxbdteujv.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtcvacxonr.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtkcuvwlsi.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gthgtpnqnh.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtlyqpuhkz.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtyqjkkril.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptbnbmlz.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtawfyywgf.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtpgiqpkio.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtdbbjbcfq.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtdoexzich.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtzyispyjh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtujeqnllx.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gteojaapoq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtxmznquug.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtshukyquw.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtzujyxuoc.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtufyylvdu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtlqygobjf.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtiwjmdquj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmunsehb.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtuunigdnz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtpmlnhpry.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtouhkzbzl.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gthvbdhahg.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtxrodmxep.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtkkltftio.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkubhimvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtragpteft.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtmriokoyg.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtijeltfqp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqphwceht.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtpchpxghc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtoijzesix.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtaqyjinco.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtvdjhdyag.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtnrtanxoi.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtzzekjaym.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtzdsrampb.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqecegvpz.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtsealpthp.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtruztnxjz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtmmwuyrrg.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtlvtqagel.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtqnlzwwgu.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtbzddlvmh.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtddnxoznr.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtwraovdpw.html


<!-- 参考信息 -->