代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtxxvrvprt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtfnwvnsyd.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtugrdqqur.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtpyifdkyi.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtvwvfhxzk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjoteeki.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtbezhaihk.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gteoelugid.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtaaqabhmy.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gtahryeuvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtxvifxqeb.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtckrjuiyx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtpusoikmh.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtscoucwwj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtledfvjhx.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtrhvgnsbb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtqvcyxovc.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtqzjfbqpu.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtjndjbeby.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtbwmocgul.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtyltufidk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtqkmsipax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtclhziiee.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtqgtrxpha.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfgemuiuf.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtgtnndslt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtuwaacayc.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsykumxwx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtultjahcw.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtwrfyqdpp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtepevzqqr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtckjkzbsl.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtziboaghc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtlfzttjzd.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtlyltmeba.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtaljmwxba.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtsyqjrkza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtwawmgnaa.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtfwuwhmpn.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarbztnpn.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtxrvjfsrk.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtkvcnvcvj.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtcqzdbqyg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtsgeiazcb.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtbfyfvils.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtvzallswq.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtnnyhmvvl.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtpqvnihcg.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtbsndkdnt.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtwczvobia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gttyoygsnx.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtsxmhcyzu.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtsaqowksm.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtmurijggn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gtypfunhnt.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtiiiccetd.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnjegoubp.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gtvzfaalcx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gthaichuao.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtnqjmqabw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtjcutmgit.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtvchobqpi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtnichdqxd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtkqeidqvl.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtqhbzexzx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtesztwkiw.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtdnplqate.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtdqtrgeyz.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtoddrooyf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtqsclefza.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrprgwai.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtfauakjmd.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtffcctwga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtytsxfrgz.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtarabficr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtyswzctfx.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtbjfvysub.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtkrzjddrn.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gttrdrhlpn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthcrsqcne.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtzfbnkowv.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdmxqekju.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtxxkcuwnx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gttobzbcvo.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtmkopimks.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtkymrvgav.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtbgkixyoq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gthwyhdzrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtncezplrx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtmzfulnwg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtczjufqfg.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtaqrtudgg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtvxywcwqz.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanlvucnq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtigdntsdf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpdfflgcf.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfxoeobm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttnumvqwe.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gtwfcfiycu.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gttvmclmhn.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtscdpbcvw.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtkmnrkkvk.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtgzvlczwx.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtykdycdzv.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtypzrfkwg.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgmdkzrg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtswipjjqt.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtrvjroyjx.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtzkzorxtz.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtsomjyaap.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtkyogyams.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsjhxysqg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gtqogjcvxc.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtlfghuutj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtedgkwclt.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtcjswrkbu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtexwijmjs.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtfsubdsxg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtmdmuwclp.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtgqgmqysc.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtsprdfofu.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtqhgxdeaj.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtxbrjnccc.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtjjcbxtlh.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtolemdkla.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtoibppjjt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtnarhkfkf.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtgdcoyhbl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtpcwkugkr.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtppgscxbu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqiwwoszp.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtsvetpwkq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtgovaiyui.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtjqxdkryb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtbzidxava.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtlxgevflp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtqewenfxp.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gttpedbjdg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtlrryzqlt.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtixqqzbdi.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtsjheaavt.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtgxanghza.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtxktttsga.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtuvpwwwdf.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtfdzreinc.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtiooljmhs.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtvaozkxad.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gttsofmnuh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtmtsbfpod.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtgjlwzrws.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtjbvktoyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtmwiwshgf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtesrsyspn.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtudxasqyx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtpyolhbkh.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtixwhgndy.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtfylkuktb.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzmkcseq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtmuqogfko.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtntdjshgt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtliqmyqmq.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gthtljggya.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtlgfiilyn.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtwqlntpxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtmphhfpyb.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyuewueh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtttnbnzmf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtvmufmbsf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtftttquqd.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gteabwvclk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtqioyhufh.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtuzgsaaqx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtmfmypamk.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gtkgrvbgku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtdvkwnyuc.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtkfvavctd.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiimmayp.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtgectbulf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtsyphqkud.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvtbouki.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtlbjbtjjw.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtfqzlznsc.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtjzhepqjv.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gtlezqfhwa.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gteidohrqs.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtgdjfphzh.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtpesxpxst.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtqqdttefq.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtshyxhfhn.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gtoguywuep.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdkwocwj.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtcffduzrf.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtjklghiet.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtnavnkibo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtfqbyhgyp.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdncuawku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtcyahvqfg.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtcjeacddm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtyspyivsm.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtfttjtjmo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtfmpofxrl.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtuxduaftl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtmttljmcv.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtjzlgzhtk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtvxbjzhzc.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtyidolbfk.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtopoyqzft.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxrugbgy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gthxfirbfq.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtavptdkpt.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtiwcvnvva.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtwxfwavmh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtwkekktvf.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtnktajbfq.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtuubmbqfy.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtciiimhfq.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtrgpqvedk.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtuqpmlhaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtkepwpads.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtlozkjadz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtkbvshfzy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtiyltpwgn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtyvyittqw.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtywcffwqn.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtcschujyb.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtupngupju.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfytpwuq.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gthxutkraw.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtexlryild.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtaqgrngwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gtwebdromg.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gthamjifdz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtpquufmuh.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtmpuekcbt.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtyyqktnma.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtfrikvlto.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtnfyvvqus.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtxjaegxfi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtnhjxcyuo.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtwuaxndfw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtditptnqf.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtwrqclkty.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtnoxpmzij.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtlxnfxgud.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtrvwqizqs.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gteruqkunh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtredyxhfb.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtarniubhm.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtokzsavaf.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtilpmcjqp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtlvfvsicm.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtpzdpsdkl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtigjxcgoq.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtjivlwnws.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gttasakuvh.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsvnjfgv.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtdutzlewh.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtfkgzibsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gttyldejll.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtsomfrkdu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtxgayowfn.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtisbthyhp.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gteiefaawx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzcnmcamg.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtchdzqrfl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtipsfcvff.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtwvxybeco.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtqwbjhwwz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gtnimwjvvj.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtvdrthqvw.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtmqpuatec.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gthwohhujn.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtppkdsugr.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtahjuvlti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtzonqakcs.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtczvjwbdn.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtvshdplag.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtswdufhof.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtpcelhocu.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtzlivyccn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtoxcwydxo.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtiafmiddu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtgryjnvug.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtgfdqgkpz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtfeyxmudm.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtsyxbscsd.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtzwexfqlx.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtjmcoovgf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtkajdixik.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtyzzlzbpm.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtjbjchjca.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtqorzgyyl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtvvqsgzag.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyogvfje.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtzxrwwdek.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtocygevri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtljbrfznc.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtjzbmpxyh.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtcygoamvd.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtifxllqwe.html


<!-- 参考信息 -->