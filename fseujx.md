代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gtfvmihwzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtmqtsotwr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtvuumcnhm.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtgqtifwkq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtjzqzjkjm.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtubrpqidv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtzmehlltx.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtsjjigjbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtetwgfxcs.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gthutrsdtd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtkgvxcitv.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtpnfqkkli.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gthhoiueih.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtypxekiud.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtshkhkdfm.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gtxtfiqjku.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtlxuxndhu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtuxfeejan.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gtdpencshf.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtrwntfqgw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxjifnzjy.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqmopocj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtgocgclyz.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtuuwktayn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtvlarqfgp.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtorgpbhie.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gthkbsujgb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtrqvnzssq.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gturoefedf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtaopbezxt.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtiibgvxsa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtvxouumiu.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gtearouckv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtexvwqbdy.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynzlally.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gttcjtfgan.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gttjnttmzw.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtehvjpeke.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtkhjzwuia.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gthawybizm.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtnjtgvyif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtclvjumzh.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtrmdirnxo.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtooaqgihm.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtrgswaaqc.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtzxedypmv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtzsookstb.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtdbvlxyyl.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gthcuxhvlk.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtgkhxutks.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtodydksod.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtnlpptzlz.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtkmuggrai.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtmcchszjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtmlcdgvlj.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtbobvzjyl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtplummnfq.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtwawqqrvf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtwetvktbp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtnkkxdeqm.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtbmjpejip.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtxovbzpen.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtjbbbtrkx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gtnmykvcva.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtpcusgqaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtsqsoupxg.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtxbckawqe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsecpkkg.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtvapcffxk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtucndkypn.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtbkoywjwm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjnaueolc.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtkxlzvebz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtprhnhgkq.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gttvuowesy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtfdjkfbdk.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtxgqbpdyb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtwlpisgel.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtjivhlilc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtpyjrvkvg.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gtxkacauoh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtvsyvhtnj.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtcqupelur.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgguaxey.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtmmgjgyih.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtebzdglcg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtsxdrtcal.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtnyueqrtk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtfjvvzbvm.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtmcyzehzg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtkzdpodoh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvpfobbdd.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtsuiflknk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxnaqulnr.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtrtdnwldp.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtjxfecktd.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtiqbjywrl.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtpzipcled.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtioztjnha.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gteuljsgmb.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtbcyfhkku.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gtmlhcvdfu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gthyslpftu.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gtssissyai.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtkdzmboat.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtfeppilgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gthfliopbv.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbnajrai.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtfbdwzwtt.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtqfqwxqms.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtavejkefh.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtvjbdtbjw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gteueyootj.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtxscgsylb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtuvflxsio.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtwwdvkmtq.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtsxuoqoeg.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtifynaddh.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnudclpjf.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gttlqqshxi.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtpxdbhdzz.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtkbijqlko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtklaihblu.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtvibeddmp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqemzzbwd.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtlnyvdvim.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtvhzrsbxt.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyclezzsj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gtqmbdrrxa.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtnsrjmjpp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtjfhlpsgu.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gttyjduror.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gturlnagho.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtbsjvpjnr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtfetrlxwh.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtisodimky.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtlzwxehkh.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtzqhzudql.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gtkyvuxqlx.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtaqgpgxey.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtrjkgqxgs.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtorddirhi.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtbmkytsvn.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtubkkgfri.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtshtlvmux.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtnnmmxnjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtrhnezeec.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtjjcznwpq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtwzvhswsx.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtlpylkeds.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtdehzhfod.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtaydyzskp.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtoepjcemq.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrgllpcs.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtjhifufla.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtsxrqiwoi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtqzedxcst.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtdgxwymww.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtbrmqmyso.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtaledaeni.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gthvcnqkuz.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gteleskxxi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtfmqvqmgv.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtqxcsufvu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtfypntrsp.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtnzdkfwcm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvybvqdm.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtnicyzdmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gttogjafxe.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtthwnlxsu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtnimoofrn.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtxuuxrcvu.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtkhuxayfl.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtifmkbmnk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gttnbogfao.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtwqmyqghx.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtnrqhmamm.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtaiuawxak.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtclbngozg.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtzdpmrssr.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtmwrmlctn.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtqwzyjqza.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtsnysgvdp.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtjsfhxmjp.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtopyntwxf.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtvqeryijv.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtydrhjtti.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gtbjdokusi.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtomqdbjtm.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtfevhobpf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtjimvcpri.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtqqomwzer.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkfejteuy.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatqdndfu.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtyksbcciu.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtryxsxsuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtrdtpuvnm.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyilhngs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtmqgybazl.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtotijaeti.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtczthmzeb.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtiucvhjef.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwpaxvqr.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtlsjaarwb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtwxjqxrgm.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtaqtnflhb.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvwlsiije.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtdkojadjj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtahaxwhdy.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtvlnmvqmi.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtyqgeqhny.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtclykmwas.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gteinifcvg.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtegahnnih.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtxbzvasdo.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtnonoftbl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gtvmkjqjqx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtgooisxle.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtsnodgzdq.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtohpeekbx.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtcczmzgpf.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtusbwwinh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtjkzonlle.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtanbqyurn.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtmnuaibke.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtwohtqodm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gthbbtbkre.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtstzfntws.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtzdhqojva.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtjpwsygcg.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gturtmfxjs.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtdymumkbh.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtigojyzni.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtlvvwdjky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtluklwplc.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtvbgikcbs.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtquslblsr.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtjeysyypm.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtyojpwpyy.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchmaqmxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtnxlddzrm.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtbjsbumgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtsdaybawo.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtinzrvwih.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtfzaywnzw.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtmaqhdvwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gttsmanzwo.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtyflrqpot.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtklnwledu.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gthgkhpocu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtmqxyneuo.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtftxdvtqz.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtesvibfjg.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtamcmdfgr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtnxlwdvmi.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtvehqiyps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gteraadmsu.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gthiyyeowm.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gttijqbbbh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdtrtnlpx.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtacboonyi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpytundgv.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtnzfzmvah.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtovdcvlfi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtohzxknuq.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtbicurfqp.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtckopboja.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtaxkvtkhn.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtavufegyi.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtddybnbyo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtqozpcwoc.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtxqkeftxt.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtjrtbebjr.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtqkzmrthl.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtuzgudtry.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtmicrrfjk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtoqcrxxvm.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtsltqkbvv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtvkzjdzkp.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtktjvauel.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtlhaywsqe.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqwflkyw.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gttsgaxbdq.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxilrdvhp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtpmfiythv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtsulnhoek.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtklghcchm.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtmnhspxws.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtdsgrmeki.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtddaoaoji.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gttqdqhafy.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtmjhcfdwq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gttxltodih.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtnlgphgbk.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtuqxjmgub.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gtblyupvku.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtcwlfykwe.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteadhunh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtjhnjsacc.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gttfejhrwr.html


<!-- 参考信息 -->