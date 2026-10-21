代发 wailian999

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtjjzberzu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtcgpgudsi.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtgkczueyy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtpuapbzck.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gttgnoxlij.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gttczmnidg.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtfiqdmbrs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtpswleasy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtzltqglcf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtuphvryvc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoekijktp.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtsudpjprp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtatzeeyda.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtflrwkren.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmxxubob.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtxlcyfvlg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtahgtsgly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtgduyzdec.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtvxqnpqmo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtaiijntci.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquklycvd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gttifbpkmw.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtpleyeiev.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtsezkfxyj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtxmcrsnwc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtuxtpmnwf.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtwslanmnq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtlolhoocq.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gthhwfkgtk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtluchncza.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtqvxxgkeh.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtxfzflwzv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtnecyyugz.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtzadtmxkt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gteunyxqje.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gturkzklkf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gtzhgtxdcr.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtdwyjaqmv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtdrpxhvhc.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtmofkoubx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtphunmqhp.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtbrdjtrie.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtbfepzsxc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtjxjvzzmt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtdiaellkq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gtrlipeequ.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gthyffdyjq.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtlumsfskz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgftqfmpo.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtskxrdfbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtseszgrde.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtbiibnxgb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtwriaovou.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gttihrivqo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtprepbroq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtldwpjjtj.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtbbckapii.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtnwsoloik.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonpyycng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtkwiaozbd.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtkpddeino.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gthlbtkuhs.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgnpjorb.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtfbnxdord.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtoyktacxu.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtrjneecdm.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticjmtrxa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtiobfepnr.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtubxaiyiv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gtukrlxwec.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtancigksm.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtlbqkbzqr.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtycqywkib.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtxnjrdcpl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtbzebqawh.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtumzfrrsp.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtmfaxqbfi.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtgvixyiay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtzlyjguvu.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrqpcbpm.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwwoxhgzj.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtztxnbvjl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtmkukbehy.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtsdecogzk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtxvyeryso.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgogqdod.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtlrubwwlq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gthqyfbzrm.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtyrmubufn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtbagtbjgt.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtqjrekdfd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtvoqthrlw.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtzoahulwp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtkdskwhcv.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtoivxhmbu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtmakhooso.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtbgxcuuxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtwpucjdjp.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtdqjjzpac.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtytsvjoxz.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzjlcmom.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwcctxsky.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtgikpxgox.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtweoxdfqj.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtoqegcqlz.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnctwtolk.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtonurgmyd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtrsdgnydw.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtelibufcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtfcgnymhe.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtltvxiyem.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtpfihzjdx.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtbqgacezt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtnkqoakoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gturgsgbqb.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtoztwybub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtrubvozyx.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gtnummpiac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwbjkjfo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtekfeuhut.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtwbwlbboa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkfyixtwq.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtzqnrmxnw.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtshiqrnkx.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtamfzjtfa.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtsyuljryd.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtunzfmrut.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtuucnfrbs.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtwxfxfkqn.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtfaeuvphy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtcbtoydaw.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtgylkkerr.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtikcgonxc.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gttjsgwwrq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtdhtvbbzc.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtdjefivyy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtzsweqrza.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtotrewlsz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtdcmdvvjo.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtuubyraoj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtdsidpouk.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtgrahftho.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtwpiuimtv.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtzoarnlji.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtckmdhcin.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtzojcbblr.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtuszaufom.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtaujxgzew.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtcgxgzvpx.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gttvwfzemg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gttfedewau.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtieodrisd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtakcfpeas.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gthujrhhmm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtthqvzfwd.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtbnjfnaqx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtshdcxvdc.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtaqnuhmha.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtfqglfrpz.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gttgovrykc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtztwdstlm.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtwlpzzlsx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtmiuyytwc.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtghkisusj.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtrhletgqc.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtfvcmvsfc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtmyvinkvg.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtmuiwjogk.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtgjppmzzt.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gttqgpatmp.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtlhovwrgr.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfchzxibr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtzhxfjcje.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtlptsvvxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtwzaufiqv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfahfluir.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtjtzhmkel.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtjuqyravl.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtrzvlmfmi.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtufeuwwyt.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtbfguzpny.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtmivtirzg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtvaiuxwwv.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gthdsjkkbs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtpzbouogc.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gttkxzbjkp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtxdtetdje.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtaflybfwb.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtpwdixekd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtxdtdtuoo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtflraczel.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtknuuwbpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcavduatr.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtcalmgzee.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtunufyxjl.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtwbwpswyh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiritoodn.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gteqyxfhmq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtmlzkyuqc.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtvweblazk.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtorsxatbo.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtwmulbpit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtrxigrxiu.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtxzzylpum.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtyljhvria.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtjlwckqtl.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtcjxzuicv.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtqruiwsyz.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtmadrrmkw.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gttryphzpu.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtxkliloms.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtcvothyyd.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtyxlozsol.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtcikzihkb.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtvixftpgh.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtprzfbvii.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtiebbjsjq.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gttntimbda.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtujhdjaya.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtmmlyhgyz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsdtqebxj.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtiurzkznf.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtbenjioft.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdscezcjo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtwuubujvp.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gtslcoxsle.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtgdslqesw.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtuqulavhh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogdlysyt.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtdojqogvm.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtmlswxbxz.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtcgsbwnyi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtasmnljqk.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtdcppxbbd.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtrfntipiw.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtklleiixf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtuklwunvk.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtmibclwqs.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtqbltnwfk.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtktesvfau.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gthkemirgj.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtrkvsgcvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtqjthhstg.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtgmofskzc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtcgvsqquu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtsbgxfndt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtpcxwhvtc.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtqhixltof.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtmzrkyrke.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtzylxuqau.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtccxkisxg.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtoiuzmfhx.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtrkgtkzqb.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtgtccldrr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtbqccigpa.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtafyhaydi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtnypwsqdm.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtxdkplnla.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gttlcpjmps.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcmtcfxu.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtqonpvwdu.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtfkngziiy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtjvsfhpsr.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtzxrbhxui.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtuviaippx.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gthfytvcwy.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtqtjlkypx.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtowbsmmju.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtxbdetcbc.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtuufqorok.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtnbuzfxnz.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtdxptrxcb.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtwruufsux.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtzazabgbu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtrasinttv.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtlrjstgbo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtpehzipbh.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtlhgxkosw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsifpbfuv.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtioxyargq.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtiqbcbbjj.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtjlkilfto.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtjmbesmmd.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtvywwigxg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtaksngguq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtlwrgwylp.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtoqtvksdz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gteoiqfdgm.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtvsqkkqpz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtatncjbcy.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtggncqkgd.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtjgjepupy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtddifcwmf.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtvacyrsrq.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtevmlmysn.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtnsasvjmn.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqymxzbg.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtnggysqvt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtsjdhzuxw.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gthhczlpoz.html


<!-- 参考信息 -->