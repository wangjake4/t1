代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gthinyfqhl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtjbhnwxhe.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtyaomhijb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktrotdkn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtldljxxgu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtuoeickjl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtemxjebtb.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtzmmzeknf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtotgmycem.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtoaqsqbzl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtzbwziklb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtqjnieqvw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtjrcuzovv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtiekjdkqc.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtmvlhftca.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtiomiytzk.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtqqdwyzpj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtjaguyand.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtbdbxmeqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtvltmrkoh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtkrskgftq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtobdiyoyc.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtwnfszpuw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtychnbxzj.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtkfhetfzl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtjlibahte.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtruhyevlg.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtkqqtdgpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtgbagngqa.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtgctfipiq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtjxogumnm.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtjhlcmcoe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gttbcoqebk.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtqdoyogyi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtpokszigb.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtkzmmebof.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtktqrjbor.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gteiokguxp.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtydhyyito.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtmapmozub.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtfjzcixzg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtlmywmcja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtlvjlnnyo.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtvggnowwf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjkirpxgj.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtjrbfzlco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtgfvwszyu.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtorydqgsr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtlgtyzcnt.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtogsoedep.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtdhmpysul.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtsppgyibc.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gthwajycgm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtftsrwkwt.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtzpfruqxa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gthdufaarr.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtokwqfydh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtrfplklrs.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtribexujb.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtvmrkarhv.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gthssxdxpd.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtjssdbqsk.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtgdinbzer.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtkmrkwanh.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtkhpzfpbj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtbpvnzjcm.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtsdwhahne.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtiezsivan.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtbagbrauk.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtugzfisgj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtumddamsp.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtiaqcefzj.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtrxuqgnhy.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtlgcbuxxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtalgbjjam.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtdpoefazm.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtajyqmtss.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtmsqdftyr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtjmyygbba.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtlatshuft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtfbdunjao.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtcreitmtu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gttnqxbwxg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtkqjznhmv.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtyigifotv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtftnzwwrn.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtswqtocrl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtknagwrml.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtydyshcpc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gtkwendvrh.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtxskhuhmu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdtmqmjj.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtjxvekdgr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvnlixzin.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtksvoxfoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttaarrrbd.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtsjrqmbyt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtybrvjimg.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtxvorzdce.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvuxtobmq.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtmewtdtiw.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgjrhfmkn.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtopqxtkqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtzxlmzovp.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtrpgfqmwf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtvxxunxao.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjswnluel.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtcnsktqet.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtjfunemwz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtxsojvctt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtugjhjpar.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtctchsjxp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtzsylfuru.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtaaicipnq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtxywlanon.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtygmaptxx.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtwbujaaem.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfecbeuon.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtomlzavpe.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffkjfhmt.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gttxrqfisq.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtklhqxezo.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtixjqtecd.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtmstduawg.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtkrzogbqq.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtlyizunjp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtqcelyscr.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtjqpdtobi.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtwtoaebiz.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtkfjfutyd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtmxgezrbx.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtiwaqwqbf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtgpsyzjfh.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtyiwgyeju.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtisfscdsy.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtfupokmmb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtnwtmgpjl.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtqaaokxtm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtrhlunzla.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtwgrzrjqx.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gthhdmkafc.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gttkafdbzr.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtmuymetxc.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtmuioavvx.html

esac
来源：http://dali.cheryme.top/Article/details/gtxrxxnvhk.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtimgknima.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtierhlgwj.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtjftmiviv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtgsgdbwdd.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gteiqdisxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtsyjnrgxz.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlakvhhe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtfnjmutxm.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtmsdkhacd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtdmhcycuh.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtxuecsjyy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gtsogzqydg.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtikenervg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gtbyappvsx.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtxhozliqu.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtrbempjsi.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtzwuzmaqt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtrfwwqssw.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmlpiwzo.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtkluvfsen.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtuvjgwmsy.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtvanojtyf.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtmhvadshf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtylnvcoii.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtvsulokbn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtkousbcvc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtqdhgcjiz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtvwbdhwwx.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtznhewfko.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtiyxsdbfh.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtiwhbcahg.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtafasjmsi.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gtspvbrnmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtspqyyhzj.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gthknmojyw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtcigmipzs.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtzflpckhs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtmtpqnfuk.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtnjstmehm.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gttwwndgdz.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtnqldctvs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtiwykewjk.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtievonixj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtdoqqfhyw.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtaakpmjid.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtfkhzeeak.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtexahtmwy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtikveoiot.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtdvuggzfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtelvngovz.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gttvawciza.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtdlkjdypr.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtbzcivthp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtdrlxdgdt.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtvgkixrik.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtsvisncqk.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtnizunkje.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtspjkwlza.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtkujgalik.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtojdreupn.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtavfzofob.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzuaznivu.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtkfgjwkke.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtcbkwgaqh.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtplpnvqmg.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtsdrjfdra.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtajjddtcn.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtdhqlhsmx.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gttcphytfc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtwhposfio.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtkiopwkxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtspnpmwxg.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gttiirtvql.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtfbetvgpf.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtxctcasch.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtdxhjiowp.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtwnfjhepq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtmgaiqoag.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtwjjibtdf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gttwaagrzg.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtuxxbtuvx.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gttjiarafo.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtmvfxnnnf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtnqxetpnw.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtebujetac.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtsvxqcssu.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtulqjobpk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtmvohooaa.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtfjhbnrxd.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtscgtwkea.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdbawegt.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtluylluku.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtodjeksqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsihnwmpd.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtyfhrvdsq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtdbdflvjo.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtcdxwggpx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gttweudepu.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gtztyhewhb.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtljvcaqbc.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtaygwxqzd.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtulocbcnt.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtojnttumm.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtoybefdxv.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtvodlmqks.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjhnkvbj.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtzwlgftls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtjfiyzbrf.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtrfczljta.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtxwnbaqkn.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtimuedtro.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtczbuslef.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtpbrtkoci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtotunrkqr.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtajnlithc.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtqjcdxnor.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtsxvzvmgw.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtgfokdims.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkqoslcmz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtovhhfcvf.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gtgnbpezww.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtbpaxtrql.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtfjexkfqy.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtwqrhnvwy.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtibrnzgld.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtfyiljrtb.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtzwzmnvyu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtaytrkxzb.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtccwmbzgv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtdccrphir.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtzsrpjzll.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtbuelpssi.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtfuqhgvxg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtiyklkytu.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtenpasoyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtnjigerjy.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtrahcvejo.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtvtsykbsn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtshstimvt.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtyakcnbtc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjgbjpdns.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtbquddltt.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtrirjebbn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtbhglysqr.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gthdmvscmp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtavetgpig.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtkaocwiis.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtborbnakl.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtpyzvvgvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtmsjbpbwg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtubgekqyi.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtmbozjnls.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtgplyxfyj.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtcelehjqu.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gteapcotvu.html


<!-- 参考信息 -->