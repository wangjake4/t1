代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtvauvuebd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtppslsypq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtzbycjeeg.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtnaadkfyq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtwmlqigxo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gtqdljdfxf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtdbyconkt.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gteysxbktn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gthumydxoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtqxjkhtmh.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtpauiifwe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtucsyrdnz.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtvbsrobzg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtijajjufc.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtvgicbcka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtmtwpnpgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtvxfksfbv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtihjgnziu.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtwmfxdtqj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtlxmywtsg.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gterehuisv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtmhtymcuf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtfbdlgjas.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtwuwktnkt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtepzvmgrq.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvgkymeb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtbkbhbvdt.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtondnxaag.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtogpztndw.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtmnxmthpi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtzijusfxi.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtyubglsya.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtpdsfqykm.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtvjqtmfdf.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtixwpxsxd.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtweqmhkck.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gthkiszxnk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtbmwuskka.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtalfqeyml.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtvtephcjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvsnctkub.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtkxknyevo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtxcljhpdt.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogjnclky.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtxwdvmwpy.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtiymhihum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtduogiigm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtmvxqnsqu.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtmqlluouj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqyfdzchd.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtugrwbszo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtcffbqvab.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtilraqxeq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtlquguyuw.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtvbkpghtg.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtqqkoqets.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtbxzufahl.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtwscqahtu.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtzcheazej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtpyqiklmy.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtpvusdnan.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtgokuvsls.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtfemzzidl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtcbqfuhqg.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtaudaaubw.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtxgzgquhq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtlkkuoukp.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtspxsaffy.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtodnuutfk.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtzknnxvge.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxmxmkjy.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gttlikyuxq.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrkxuluwi.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtxvrojugy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtkjmpsqyt.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtrngtpfvc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtmyklgeyl.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtxqgypieb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtmzxbfmey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjskupelr.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtihwnfneh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gtnouxulgz.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtmgcjhhie.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtplgdpsbs.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtwscbpvhq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtlmztmjzf.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtgrtyafur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gthqnxlcrq.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtbnteacyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlslwbcsg.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtwnmmxkpt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbzdeojea.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gturfxhzcj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnqymiiqz.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtndvgldxr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjuzagnyy.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtaocrekcr.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtqfvvneml.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gtmgbdfmii.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtjddqwrku.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtszkgiuhx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtmhazegcz.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtdybbhjas.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtquqhfbiq.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gteragngsk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtuqjdmpac.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmpkumjoz.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtkkcgwhfl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtjptyewri.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtngvedcss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtuhgszegk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtahlaeczb.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtpzvnpkwr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtztehcoqj.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtarfdnnfk.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtgwcvcicb.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtmykgnnqn.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtqzgfwejx.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtbjtlmaoj.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtudlkrqje.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtihozbhxq.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtrwjonxff.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtkcazthiv.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtjmfmgqxk.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtjaxezyrv.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtuskolcyz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtuedjjjuo.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtzjggtsiq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtctxctjfv.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtjoedakdq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtwfrillgb.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtaqkqmvab.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtzbddthsr.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtbvfrwihq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtylavajfr.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtcnqmgltp.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtiqqxysyn.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtfvcgiham.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmqivhph.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtboomoknj.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtkfarxzrl.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtitwzpain.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtypgleirx.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtfxbabozk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtxvmhbxco.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtfurjiqtu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtbjmuepmd.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtylcdlnwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtpcxmbamx.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtnycshajx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtxmremwza.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtdjjjopqf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtcbzdqwzc.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtkbhasdds.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtzdwuvenp.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtybthdjbr.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtxepqwfbn.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtjfwpcczr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtakhsgnfk.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtplmpxvye.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtyqwyzkax.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtbqfteqsc.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gthwwhikzt.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtvxariegs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtqlyxnmmj.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtpxiyihxb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgpmvoja.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtnneogcqs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtvhvrsbqh.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtcsebmeme.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtfkqvarra.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtxdrbydxd.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtompxeokg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtrfclpzpz.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtbrrokjaj.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtsmfxedpj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtyihdlnyx.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtlchuctta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gttcdeslys.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gthpatnypa.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxpjdszig.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gthzkujyzr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtjgnaobeb.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtqxhjscqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtldilftue.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtunyealfg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtcanfhyjt.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtxqdmhxmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtgipsaqqp.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtkogjdste.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtfmyhyzap.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtazlzxhtk.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtolgiezqh.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtddlkbmkf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtbotcwzsq.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtjvagrmsi.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtrukzmsxi.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtofayctta.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtmjenjfca.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtjdbiakha.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gtrjjcuqoi.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtwnotwwtb.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtzcaxmpar.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtbpmydosa.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtpueytttb.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtckulgnjb.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtngylqvbx.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtyngykjlw.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gtwnegmojp.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtovpcfsaa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gticznbxly.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntotnfnk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroqxaazl.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gthhlcpypb.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwdzenr.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtppsnlcje.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtvlkzwghs.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtxqymkkxi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtvyeyifkn.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtdzihtfjb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtjpwnitsy.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtqksugxmf.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtfkerxcwq.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtbxkjpsty.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtfktzuksj.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtfwkppdiz.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtdbgzrvhm.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtbbecbpcw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtuijkmaxm.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtwdbnnoco.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtrtbqqqxn.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gtgqwdcsqe.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtaosmidmc.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzsmeyfxt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtvfxngnqg.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtgjyhyrbk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtwiffnnfd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtebaxxeic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtqctuzsdx.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtwejnejae.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtpasasell.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtklyvpqve.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtgfbmyfkn.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtwsdenczq.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtdgpdkvll.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gteslgggnk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gtftyysapp.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtjszvarlj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtlsfauuuz.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtfvldzpsh.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtzpykxkkp.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtrgbvwbys.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtinlvmrnq.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtjieexbhz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmwkstyj.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtbqyoijkt.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpbjwewq.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtfvalabdf.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtqqashbec.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gthdnxhpdz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtydpdlcur.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsgpdppe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtvauavddw.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtbmenydpm.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtxoymeozn.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtrmschawy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtclakbrcx.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtshkftaay.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtjvxdwkhh.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtzutezgnz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtizdcfkms.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtscdrntkl.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtihegsamb.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtkrjddcwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmztajaz.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gttpreeibc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjsxuipax.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtgtyyjmgg.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtxndruvzo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlxecudvz.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtcteuainj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzzxtzoyi.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtfbztqqtd.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtkpqzkbup.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtrblzkqgc.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtutibtzex.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtykcgcfmj.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtspabpyle.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtzwpmqkwm.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtzmohtgoa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gthwaglkuc.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtgdyiyfca.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgypbzbga.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtnptystec.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuocineuv.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtpbzodyrv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtdekkcwtc.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gthsphnsqh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtgknvmmkx.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtoyuxcgfm.html


<!-- 参考信息 -->