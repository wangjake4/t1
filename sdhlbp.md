代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2eiuvregh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2jukrabpy.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2kdpyecwz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2rsuixdhb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2rkboejji.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gt2mfahqxqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2atgiqhvj.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2pdhldcoz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfsrlggk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqkziifa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2hatnkies.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2epzherxd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2zfeqhcpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2vownvezd.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gt2vqilqopn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2bbjrtvjz.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2qryfllwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gt2swiryqfg.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gt2iuxcgfah.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2xijkltzy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgbckrfl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2evspkeut.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2ctubuasn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gt2pmfelrqn.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gt2oezisjby.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgncvd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xarejobb.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lczvtyjr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2qqbmeyoz.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gt2uzllpfge.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2yokgpjpi.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2nbgwcfcl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2eercqknd.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2jsvyvslo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2pdunrpgt.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2eidjflzd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gt2pplexmhs.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2eatwijkv.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2yrwfohpu.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbfaccqq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2zonupjla.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajigycqn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2lzmmuoqp.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2xygzgntz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oncnatam.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2rrnzsccv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2tjtlklaw.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gt2uncqftha.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2johhmeec.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gt2rumrokat.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gt2iaglmdaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2grzzkkby.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2cktpehiy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2hhjlitfd.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gt2opyhdlcp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2xybbiyyh.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2nfizsjnl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juzrjwia.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2jldwbuhu.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gt2lwzvesfj.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2fbdhvfxu.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2zochumoh.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2qwofgkdn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2obphaoxr.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2erlrobnk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gt2yspbjruo.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gt2jovvvtqq.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gt2eozusnsw.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2nyxecoso.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2zgrxadhd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gt2rzhabryo.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2pubebowe.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2fwsujwzo.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2mbwfpsiu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gt2zgqrehnm.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2brkyxmhp.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2rqenfxep.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gt2kmmmqcfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2okgsapaj.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2jbwllvju.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gt2hlotqfin.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2lvthcvnt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2rkmprvbi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gt2uiervuhq.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gt2jwsucqom.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gt2klkkvtcg.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2iaezxwsa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gt2lcqyryum.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2dhjxhnyl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gt2ntnyulye.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2hczaecgp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gt2ewqutlnp.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2fzcqgmoc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2hwmlivkq.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2mgnamhrb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2inqwhleb.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2fzekhtcy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rjgijktv.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2kxrdholx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2mfgtjjtz.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2pkzlvpss.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2kjotvqrh.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2wlkntjkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvquyjwt.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2odwvmxrf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2wgdjjvlf.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2mumqgokr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gt2ncfnhtiv.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gt2iytbqxzc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gt2dbyxutls.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2lixgcdzp.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2nxhwszcl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2vsqnaveo.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2tqgnagop.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2qenhpapf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ccoeznhp.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2spupbagi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2obuphzes.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2qojyrpey.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2icqkhndh.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mklvhnob.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyjdbgdi.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2hfxvatkq.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gt2gnjzaueq.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gt2clpbznwm.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2prgmidmi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2wuynkbmy.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gt2wihowshk.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2jxpeztxx.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2mneyxbto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmvltpzt.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2stwgighl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gt2kpynmszt.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2ikhbczbf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gt2umpmsfqr.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2gxmuzobk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2xaplpegb.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gt2rjppuygk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gt2vlpletec.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2jccomzer.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2yjgtplmr.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2jwhqsqsk.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2ksszdgia.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2jwxkreir.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2okkfvyge.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gt2aymbjgti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2gvtrpcxb.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2dubyvuwz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2onpposwt.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gt2eqlokcok.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2urlawgia.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2vfvjjntq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxbypjms.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gt2vwchfexr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2duyzmysj.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gt2riwcxwbu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2dohailpf.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gt2bbqdgfkp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gt2vdygtley.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2fswrxezk.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2biyfytbx.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psmxkngb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmottsn.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2wxcumdyy.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2afgbajmm.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyrsubha.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gt2taoefysc.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2etibfgxv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2mzjxjdwl.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyruwakc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2nxcoxfkc.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gt2jqxondtp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gt2ioixeyju.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gt2vhbrnmmp.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njhonifc.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2lctiyooq.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2bbfyjinh.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gt2wltdkzkr.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2iuffkwze.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2scvllqeq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2wbciuhse.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2bxexlupy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2ysgsdiai.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gt2smzodnxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2scdsffuj.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivxceugz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2kcbrxisg.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2gsqdtuzg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2zllowita.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2xlsvlwod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2dpdlhldn.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2bqmqphwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gt2nbpyodjc.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2ypvcbikl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icyeugcs.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gt2qifceddn.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2tzcdgbpt.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2xxoqfgph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2cmgultte.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2gyzerdem.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2zxxdzono.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gt2qzwddkjh.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2xyprdaal.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezqqvppy.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvlawvvb.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gt2sfzhtaqw.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2hjkhdzgm.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vanxytig.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2qrwsbill.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gt2ivcfiktq.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2gqdckvci.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gt2lhrhqtya.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2sspltspr.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gt2avwpbhgm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gt2dzsmigqc.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gt2rlcobzjx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2yaajthkh.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2ummvjsmp.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2ogurlxgp.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2nbytvmyk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2ztyyqbtc.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gt2oxshagkg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2odzivuhz.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gt2kmsxzfak.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gt2tgnxrtbl.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2megqcfla.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2dvjahiou.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gt2nancxzkg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2kjajbuqb.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2rlmtnvlr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2noercice.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfjhyznt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gt2dukoqevv.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2ipxuskrs.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2gybtsmjl.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2tbrowlvg.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gt2njnqlwtg.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2ogzxyufi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2nigkkxyb.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2pxaunack.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2gufsfbjb.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2lidptqmh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzypkdte.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gt2qikylxgd.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2dplkhbzk.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gt2nkjavwkw.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2rgiotstj.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2fejtpmiy.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2kqdykkpb.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2frtpxaqh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfsnqzid.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2ecaxrjht.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gt2iavdypiu.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfijuxaa.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gt2ghttmfwa.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gt2azihgpdr.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gt2yutlwyjr.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2wqwxjicp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2gkcbvacx.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gt2xbprawsg.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2strccmvh.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2vayghusi.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gt2bpdbjagj.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2tkdzhapb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2wakirnyy.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2sjdrckwd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxbjpkrr.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2abgpwlco.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gt2ekjiobhb.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2wlmfwpff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2nzedkpbz.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2uxzlhfpm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clduxtnh.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gt2fjsspjmz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2gwbxhluv.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2xtbbdqct.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gt2imlrwuml.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2ecucugkx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2khsbmhjf.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gt2eqplmkmn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gt2pfgqiecd.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2ecpeksxb.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2pipdjobv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvedaacl.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2iwyzogcl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yiedvffv.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2ejrhtgtf.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2nbqghxlp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2lfmbqlwo.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2crfjiyer.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2qgkumyur.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2lrjddqas.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwrszbpa.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pshzitaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2iktjlank.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2aczonlvy.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2bncfiqww.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2dwwuvicz.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gt2ybfmfdvd.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2lhjvkzdd.html


<!-- 参考信息 -->