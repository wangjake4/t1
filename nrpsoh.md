代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtotfmhsft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtgiehutir.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwlbmtnu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtodqmutau.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtlgpkerjt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gteqtecueg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtrncueurk.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gteggzzzyb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtjznglxhn.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gttoxxnwkn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtmxtljicw.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtfnsydeck.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtlbbwotzg.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtaqbniqat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtybrnhamw.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtdjzqkjol.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtawpybles.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtztbozfzo.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtxixuhoym.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtvdjorqoh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtkbpfoxun.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gtuhalhulu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtuzvhvbqo.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtztvrtfmk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmyhdeysj.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtsxapnckp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtlkaubdnp.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtxqfxftdt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtlyreaqpx.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtfmkixmuq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtyfzqxgql.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtqinpjbud.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtwpsdlahm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtzisyhbke.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gtbznsjyzl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtwvckxyml.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtapkbwmtt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtignqzkff.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtquevuwru.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtrpgrxaiv.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtuusxatnh.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtzlfwmdno.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtngmibeeu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtxcglsmsm.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtvgkmhuuv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtmedoqcnj.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtwjntyibo.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtiztywfpo.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtfwidwwnz.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtybtxyhoc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtyarhlmjz.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtvrfwscdc.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtwpfpbots.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gthoqzfpbx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtktdanvkk.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtwhsyeten.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtgsrjmsne.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtjcjlljml.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtrjyhstdk.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtqzjzhaik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtehuysezh.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtxqigppmd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsygabmhi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtwhimqhbo.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtrnldwmlz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtceegvldj.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtoxnclxai.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtcizgycki.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtsibvyvcw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtmnxyucgm.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtpihhciux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtqqrhxbmz.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gthdsssqvt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gtnxbpdgou.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtzhnozqjk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gtqtjvcmca.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtutzacuky.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzmttsyau.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtygejhehi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthwqstpmv.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtdeuknish.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtkxguahgh.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gthpgvshts.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gthmnuhfkj.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtnhraleja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtraizyyea.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gtvwxzwkeh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtafazbjvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtodedyuqx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gtmgrftfpm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtcpscvflp.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtiguoftsl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtxthxrirp.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtmyegpkfy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtpejcqxxf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtooqmtsul.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtpikanlgh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkzmtybsw.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtzpfntlpe.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gteffvqenc.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtfctgfdhx.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtongtlmzr.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdinqgscw.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtzujdmzab.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtcudvuuoa.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtwgoapezt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrarebqo.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtvjxoprey.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtigrfoemw.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gtzcspihnv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejlorffe.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtqktnxeie.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtjvyuvrmh.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtwvvamjuc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtkdsfkb.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gthyeqjcvo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gttoysdpoi.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtzanebjvw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gttcooooby.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtiraoihip.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjtyaosz.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtjfrulghs.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjyblmej.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtgdcbxfzm.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtnsooztpl.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtmeuxtxut.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtbaivnlbf.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtncqoaayp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gthcnfzhnw.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtfftikgrc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtsujnjrax.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtdmrkgeqo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtbtnyyeeo.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtdkfrkveg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtpvjnhzij.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtgyvzslmr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtbaawqjud.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gteeeddjum.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gticwswvfh.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtkgbjukml.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtustewlky.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtiigkusgm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtdaepyjek.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtwzkvntle.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtkjgjnfsw.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtpfsgwzfq.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsvcbxhg.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gthmntaltf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtuezcnwdb.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtxptznlgr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtempvbdxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gthsmyyusv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gaohongyu789.top/Article/details/gthwhjqfpk.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtwbpvapyg.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtnrcxjagn.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtikfqwamt.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtwydwbuhj.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtbkyygprf.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gtqdudfupp.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtvwtzsxnw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtcafrkvfp.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtljllloeo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtlzkgqezz.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtpaysqydk.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtzfejburl.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtavycvrqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gthaahkert.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gttxihqisp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gttwdqzkne.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtnqlvrwbf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtsmgcscmq.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtlvumydqe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtnuxgusdf.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtesqmyfsz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtpsdggbtl.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgdawhrug.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtoqvzitfy.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtoobsdicu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gttifkiede.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gtnmkqhsnn.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtnxrpxabc.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtiuynodwj.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtmdhulnim.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtiekxvuje.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtxybfssue.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtunavqdmk.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtymdfujlr.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtwjqokulb.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtdshhrcqf.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtqoopmjdx.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtxfxhzvtz.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gtrwkbtnkq.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtutwkkgvd.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtfbpqcuvq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gttdngnyxr.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtihstbkvz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtqwguoszv.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtpwrxbnut.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtsmnkrrst.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtqgnhjrrx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtphymenfj.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtkrkibdso.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtmyukfani.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtuahbzcwn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtybhpmqgm.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtogitceec.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtrrmscytr.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtvgcnybwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtrgptfffn.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtnztnsrvq.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtzvixmvst.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gthhwohgws.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtnnkkqzbx.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtogagwzzz.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gtwtbsvqqi.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtdawbetbl.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtgnmksnau.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtdqxtmjeu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtsylgncjw.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtounxaqcw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtcvqznpel.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqgdvfah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtqekixrla.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gttrxndupu.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtocvxaxch.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtqrkcdgal.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtsfwkyeea.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtryvxzvxe.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtqrnjbtro.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtnyokzwgu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gthdtvmuas.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtrdnlpjkk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtankiuawy.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtsvucozfn.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtimprncak.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtpllyctqq.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtdspfjjyb.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtqynpjwsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtyvkjudgm.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtbgqaaxja.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtyovatlgp.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbsmwqff.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtuydhjngn.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtcbqxeosg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtdmojbdkz.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtsahtuiai.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtvkulemta.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtekcfzojm.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtbaladmnt.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtzuyfchpy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtytlrgkur.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtjmcjadpp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtzaeyojmh.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gthzhrdadr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtoyqigqvp.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtrljbslxq.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtsonpcalb.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gteujezliu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gtmvzuixlv.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaplqxjj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtlfqjebgu.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gttbepzqwv.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gthpauxbir.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdqaemcds.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtemklfrue.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbugzszvo.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtgsbzqsva.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtwugopsuc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtctxnzcsj.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtudoetpdn.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtrqaajian.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtbowzdxsg.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtjifwzvpe.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtwaauejjv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtlclgezzg.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtxbqqhbqh.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtyheixflq.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gteqfopgue.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtclzrnisv.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtwqoqjcaq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtrkvtiipa.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtmneweiuu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtkkhtqlpx.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtpsquygwv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtywjoeubf.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gthxffzxbk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtuuqrywpr.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtsauqkyvr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtmeavzjzb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtholgrkyd.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtrypncvsg.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtlidhdqnq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtlfbewutd.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtwqzgyymn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtvbbsvkgp.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtbboujzkb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtkmlgvzmf.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtedpzsjwi.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtbwdrqjtn.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtrvaazphx.html


<!-- 参考信息 -->