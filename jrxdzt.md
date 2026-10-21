代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtkrcakmii.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtvzufjipv.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtbutulwec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtiyxruoxm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gthmgzbzju.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtzhsdanwz.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtflwephgh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gtaxjwlhpd.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtrfoixvhv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gttitxxnjt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtckpmsqbw.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtsbrmxkni.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdumtelvb.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gthcbucrtg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtrftcdwgh.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gttvikojym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtxunrlgzz.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtjitrmkeq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtzilrjgkn.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtmllnfqql.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtgiqdiadx.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtlnxhbjox.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtiluwtxdn.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtjclukijb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtisiqwqhi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtdelgaipv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtffnxcmth.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtesvomkfg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwhcizsfx.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtkeozdafq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtwkedevnr.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtjogecvux.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gthgyaipno.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtixtdlotw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtmtgtarka.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtxbpjfspj.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtnlyzhhkg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtecjwiajw.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtvanodzur.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtsjhzyzuc.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gtimlpbjtc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtckzgsday.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtogqcezio.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtlftypqgz.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtymvwofur.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtgvfpirna.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtlkzotabw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtgfligxfy.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtngdajtet.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtvqknrvwe.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtmakidtpz.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticcdbqaa.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtlasqlmzi.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtlpurzjaw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gthafycaep.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtpwrbfsxn.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswxxdlhl.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlghgippy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtszlzlfvd.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtxzmramdy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgrmskhuc.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtkahuoamw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtucbfhpuq.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtusrvftad.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtpkegotaw.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtfbpjncam.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtimivbvpz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtfxczwjev.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtlrmuofwo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtvrmeehve.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtzpgvorss.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtelqwbcjd.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gtzkayugun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtvybustci.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtxoytxekm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtjymmpxym.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtcxnmtntx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtpvuzaiyp.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtvvrpypoh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtopkrahgt.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gttcsgrnrz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtrjtwheod.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gttlwdxlli.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtkuyqwyai.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtsdvnairh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnqfdytoy.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtvlslkdkw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtomduwswo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtdzpqtajn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtsygcopvp.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gttbrezcqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtcmfwahet.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtzuebelze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gtgcnfefii.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvnujlqyt.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtvcpkbjbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtgrikptwg.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtngfbkixm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtjmyfwsvw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkbguejag.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtojkkkhvi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdsrhpzmo.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtcqdmusqf.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtysnxawxi.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtoqslowse.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtkftsyhlb.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gthcgsyhgk.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gttlmefnbc.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtpekdplbd.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtpurkpwzc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gthpeccikb.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtcmrapxeg.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtrurkvfjj.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gtdnctheqo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtypguzgse.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtjxgcqhhp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtkutstnsj.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtgndzxeam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtmfixyfzc.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtgxpculxg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtawgsriwf.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtfvaxasqk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gtgrmnznxu.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtmypegcny.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gttfxqkzjp.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztexmbzg.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtcujcdkfw.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtvioilnlf.html

esac
来源：http://dali.xinyue.icu/Article/details/gtuabntitq.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gthkgpmwqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrooaokoi.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtrfkdmxmq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtxypmbwec.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtgbqgjoct.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtaywaxpnf.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtvwppityk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtjukpgbqi.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtrhtfxdfx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtpvnsfacu.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtmosaomjd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtinycrmox.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtctfensoa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gtkdbiaksi.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtnswmcetn.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtbtqqoejl.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqixblbhy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gtrnhvivvl.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtfkofujnl.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtjhdaexox.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtfmizfdbr.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtyvjxnqqt.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtocgnuput.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gttgxltfnw.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gthsggbfrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtmxcwibkh.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtrxxxcwjk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtcbkjggym.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gtxywcpvac.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtxyuytvpe.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtwazajanb.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtoiiyhied.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gthfhwwipg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtaydhzloe.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtsilatsjn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtjrvjkpcy.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtqfaakjay.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtkiziroqi.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gthbdiezhy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtugldwbpg.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtqbnfelyk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtutnnywkl.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtaoonouga.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtyfvoppme.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtipesceqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtxfmewqkk.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtnlcuqxbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtrdwzsbfk.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtvdqnvutj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtpfqobbuw.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtjpewwrct.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtzdfdojzy.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtyvqrfvss.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtordoqkff.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtlloddgum.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtckvalvwh.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gtzrftnurl.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtdwotupkt.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gtryiattda.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtmenjphqe.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtckyvtcwc.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtxaornccd.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gthqotebtf.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtpgdlzpqx.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtdqecxrrc.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtonwqqqbs.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gthjnbcqbm.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaywdnsi.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gttntdvegd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtkekqldyy.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtsbomnjkt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtdafpefuv.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtrlqtiqjn.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpehxcofe.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtwrfewift.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtmzrdfjvq.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gttibvpsyw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtdlzgfckg.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtgcxbipit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtckolnzbc.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtgusybobx.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtyulpuyjb.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtdkrmuaks.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtkbpbaxqu.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtqugepraw.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtaozysfsn.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtevxcexdq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtzgmbxdre.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalwtqgig.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gthhzsuvew.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzltazqyn.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtlokqypgw.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtmsqmprdf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gtsrxwkuux.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwguablu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gttmjjtuws.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtwraeozml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtpnoaatwy.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtosmmgnqj.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtpbnuytpa.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtjpupuash.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtkxegahjy.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtqpvuvbls.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtjpnciljc.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtoqtljfei.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtcciqdkrk.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtmoyxabpf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtytgksgnp.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtligfyjkb.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtguxgwwrp.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtmgoeizsr.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtxngcihkb.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtfxglwdik.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtogvcasxr.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtnnbyvqla.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmrhveuo.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtxzktoyvg.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtkdgdthmi.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtcbhgaeqy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtpuwvnrya.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gtkkcgdqrl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gttaepnfea.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtifkfdklq.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtsoyjdofl.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtwnzehghb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtdeenvxwe.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtkhvmsvmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtrzqunabr.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gttxqqdjvc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtefhtnvgk.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtekqltiiy.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtoqnjwrhl.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtsiusojxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtwzkmvlfa.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtyxqljyoa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfigxjybm.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtregbddwb.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtdcfcowzu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtanfuhuyv.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtarfuligl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteomsvbrg.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtehqqhfqc.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtxssfovff.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtvnsebxzq.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtgrtaxcej.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtoujyrqtm.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gttvevitml.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtbtqwzvpy.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtrvwfcrek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtofewqowy.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtphdteofj.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtrbemdcqf.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyqebukc.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtqigofkdq.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtmbtuzuxz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtyvzbwuap.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gttstzomnc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtcmsdmmci.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtbbuskxqd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtzkfmeiop.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxunmvna.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtzttyhfic.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtigcgnduw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtxmxqrsvy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtuurzxivc.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtkekhzvuk.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtjgrsfeqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtffqvamqt.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtmtfbmsrc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtlzchgoyp.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtubiatmep.html


<!-- 参考信息 -->