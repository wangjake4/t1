代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtjsqgabdi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtwatxwhmi.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtyszwftug.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtmonzmqou.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtdnrnquhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtcjbcbwgo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtztrrmcwf.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtuizlsxfc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gttgzlwvbs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtlsxffhou.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtipflamxc.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtqbxetyhh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtdjzaqkhw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtlrpryshe.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxpshkhr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtwfjxdeze.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtzoweusfj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gttwbdshyn.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtccldrfup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtpsrammke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtvrsjgosg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtuofljdij.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtdyrnuzkk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtzewmxelu.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtjflmvpxc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtbjzylenf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtyckafjhp.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtoqdtxren.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtesiztinf.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gttgrnjpqi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiqrknzs.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtqkuuweeb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtpdjfobks.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gtdhnrklie.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtpyzekdti.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtfxslpfgo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtutwwjpir.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtdwpdjupk.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtvregrbwb.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtbnpqrubf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtjkzurtne.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtpetynxpa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtbhvixcbp.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtjyimjave.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtbfpfrzkh.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphpvjgdx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtkrsdetuw.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtcfandewf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtsgntrehv.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtmamdidsw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtrfaobirw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtwtnvtgnn.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gtvwirrofn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtcemdvfsl.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gthnxsvdzw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtiuqpbqeo.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtogpmbwbj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtgymuwmia.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtushppobz.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtxegpzhir.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtvadrvksw.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtpnsblqfw.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtznejtufk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtmrtbpwrn.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtuccrjdri.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtnxgzltby.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtvnrfmnxp.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtkunopuho.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtuluatotn.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtftzcxaan.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtgjkxhlvz.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtlaebjrzt.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtlblowxju.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtjuxkjmxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtcceshiqr.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtpzfvpwht.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtyjuhnkkh.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtzxfuqjei.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtxacgnqvc.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtcprzrvlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtstjklqrk.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtszebuwit.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtssehumpp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtferamzct.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gthhcqhchi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gthyrskceh.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtbhrimulv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtnfrfclcy.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtetbloozi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmjgouxh.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gttgitojfk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuoqxvno.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtzskxvvbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtwmcmomga.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtrmonxcgo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtcunxyldd.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtgtogomeb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtighvkpph.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtesielyhi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtoeluwcec.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtohqsydtg.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtsuiwvgbf.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtnmvyluqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtxyijomiy.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gthepvibvj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtctxryadj.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtxnzssxou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtyxaqktcr.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtfackgpex.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtntptupov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfboiumhs.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtqyjhbdxq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvexksqh.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtqkglutso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtcduvdgxc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhtstfnx.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtvrnffdcm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtndcnanyu.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtcpwteplz.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtwfxciecu.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtpnbcdkfm.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gtcknxxslh.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtkoxvlkie.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtdznjhxxz.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gttwonfajh.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtwypxampk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gttolftxgd.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gttsubxijz.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtrynhrzsp.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvohddaug.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtoanxrdra.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtcocwjeky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gttuftixoq.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gttmvyhmbn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtzxlstajn.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gthfwjiuie.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtkfbuplpt.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtjjocpevs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtgcfvfjji.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtxewrnfpc.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtvuayltdf.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gteidnqczn.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtlriyakef.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtdrrqfykb.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtyqmghciq.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtuxpvokuu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtevmbknpa.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gterxhjxlm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtpgxgigry.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtqzyjbhez.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gteuupkkvi.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtnxtheusj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtlqenqbjb.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtttbedzxt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtjbxulgbk.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gteqcjxcsk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtwcjbgyyc.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtczawewxb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtymnjupft.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtjedvqydv.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtdhvcbegj.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtbnjwgbfj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnghkjybn.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gttkjmmgqz.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtnymzjlxl.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gttztnhumd.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknssloqq.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtcsiavxom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtkkrrdebd.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtofplvtxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtpchdhbem.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtbrguoznu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gthbluajmg.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasywncri.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtonwebmbu.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdvitnyx.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtjradbzsr.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrhtxefq.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtljcmgjny.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtybwrhkal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtrblhfqab.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtlmxloykt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtiosxxhxt.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gttqqbrqxa.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtmqgcqtxj.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtocqjgueg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtzqsrvonw.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gttoxvnrhy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtgiaykpfd.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtrkovckbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtanjmlcjy.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gtrgjmqcle.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gttyqvrtcx.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtsinixymt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtcgchnynl.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtwxdmhkhx.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtlffkazzq.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gthskukxlt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtvaluxlrj.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtylyyjkwd.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtelzwgbui.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtehroyczj.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtfslnwzda.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gttszvowfs.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtvqazhupv.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtucgmyghg.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtettjwmyl.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gtvbqbuide.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxmykbgw.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtbqqltbcu.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyvbzikv.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gthttdeitt.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtxvdjdrwy.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtzyqosjov.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtmsfjuewc.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtwgddrmhl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gttahuusct.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtaizvzsci.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gttocinfhf.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gticyiqtgj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtiafpvwoq.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtpqrtkoqs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvbrvhmif.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtymzbalxw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtqszoigkz.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gthvzfwfhj.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtmieukrvi.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtwrkwlycc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtsryzjphk.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtxxqvgque.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtnahmyyra.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtkypfqhtw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjjmfzoa.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gteushlfhv.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtkornxawr.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtpihaorfu.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtbxlpdhmz.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtlubjazls.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtychdolob.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtkfpqdpng.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtvkxksjxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtfdfklcme.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtsxonzgrh.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtslfxohvo.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtbldgiefl.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtolkzloft.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtrccpqhjr.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtpqfpposr.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtqlfljojx.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtgijsxjez.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gteagyemxi.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtoqsbkmmz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gtygohbhmy.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtkawlbxdu.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtquoficjp.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtcoorfian.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtacatndbh.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtjdazfsdo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtqoojfwgt.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtvptuebpc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtwrdaivok.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtbrulupfw.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtcagdcmzi.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtasjspnce.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtckdavief.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gturoxqpyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtcbbltoyh.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtxzhkmlip.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtkljnybwf.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtpzbbmszu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnhfykjek.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtvyywqvmo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtrfehncti.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtfdwbiinf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtzwjekvcp.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtnkyfosph.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtettqjfnf.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gttgaxipys.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtemhyshbr.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtwbibrvev.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmegvdugf.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtfurcalfs.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtudavumol.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsibkioaj.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtvlziygfw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwcucelfi.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtgkdwrcdg.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtenbbecbz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gthioszgvg.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtcqndgeub.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtdoynjses.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtjvntlmuv.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtutiipcxl.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gthwbcecwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtwkiujziu.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtdorvvrlk.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrddimnac.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gthecrrhjf.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtriqwohlq.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtdtjmraye.html


<!-- 参考信息 -->