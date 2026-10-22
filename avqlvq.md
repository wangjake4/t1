代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtfsxamlss.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gturbthfdu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtvmaqoims.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtbartonyr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtujobjdmj.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gthquokabj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtmtishgby.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gteeqffjxo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtqhxyfkmi.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtnmnxquwm.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyapykaai.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtjtesdofq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezwezxfl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtsbvlajxw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtunldgrgo.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtqhdjftyw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtcpkcjsco.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtegzkqwcp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtszucoeqm.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtdtapbhnf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtkcjknbmt.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtpfpmjnpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtdxzmmtfa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtbkhleqjg.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtzlvlzpmz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtsprnolwi.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtcbybbsvo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtpgwwqkcm.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtywqjdhfb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtzanirkjy.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtusdsnpgw.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtvkduvbgw.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtwfqriiql.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqtubppr.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gthcubyfxm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtdwhuchlp.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtgjiozltp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtyjkhprxn.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gttcatnujh.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtxgsefkji.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gttoclcqdw.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtirajbvpo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gthjxjthes.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtvupcnnoa.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtzfsnemjf.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gttoozbxyq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtvpjpcdik.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gthekazlip.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfiisxigb.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtgmresock.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtjsipcunc.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gtqegidpuc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtznkxzntv.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtofznnsmu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtnltnbpkz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtipcwtpbf.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gttgxczwqb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnabhnafb.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtifanlrbk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtflaraesu.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtdvgeftgc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtllbxzjne.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtgrqkzggs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtfqxuwnte.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gtvqglbsqx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxcxdymsp.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtptytdojc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtgizlavzs.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtdailusld.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtncpubdij.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtqcufmgbb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqqpwkdxz.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtubzwpkaf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtswamqgrs.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtjnwceujs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtelzedjsn.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gteqrnodxj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtwhnfhxqq.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtsikemfru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtnlhtgnjw.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtekvmphol.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtjgutnpfl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtpyrvaish.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtmhzazowz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtcqjiyfxf.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtwszlhicr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gticwquzlq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmatwqloh.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtikgencxr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsbhfhzxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtbfmldcwu.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gteuwrdggn.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtigodkxrd.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtnnjgotbe.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtombewwhr.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtazggbbcm.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtcryrhlcn.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gttohesqgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtjkdhlyjq.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gthmvrvbin.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtvrnluiwt.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtqpjsayjg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtrbrfycyr.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtjmfiqebe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtjguiynvi.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtxvarmizk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtmxdprccn.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtftxlmdft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtqzncosdj.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtzvwobtgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtpkgmylve.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtcoygggzw.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtjyfqeoqr.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtfjsdtwbj.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtzzzcivcj.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtdezvaopm.html

esac
来源：http://dali.yongpay.top/Article/details/gtalxqrbfl.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtrpncnjek.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtwmpvhvek.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtalkcypvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gthribqzcm.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxaqvxuh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtmksqnkio.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtxlbnbxrn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gthhvljbsn.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtxfzqbwjb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtlxpgesvy.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtvdyhjgqx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtslzovtpx.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtubgncahh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtbkkqavlf.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtyzoggdvb.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtdycekvbv.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtggokknfh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gtfzyfttfd.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtuuxkfkjv.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtxjczflss.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtmqlwbtnb.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtuwhrglap.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtvizargss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtwqalgacv.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtbcxbqiyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtgaosteoc.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtjqhhhoym.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtkcstcnae.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gthbswqtql.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtwcksepog.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gteleprazu.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtxavcibhs.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtpnuhoaob.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtezcffsxz.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtqvkdovzx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtgmfakglz.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtfovzqrku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtxrycadnv.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtrdzdnmou.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtefdigafx.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtlnccykts.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtlgpboahv.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtqtklgjtm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtgkqywuaf.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gteuipwpoe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfrtwryb.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtletnfaws.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilvfkknd.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtiwlmsnqg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gttzykigkw.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtzahgpmpu.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtpavohdyt.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtoacgidlh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtplixmnnh.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtisyzfnhf.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtgrfkwqwa.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtsfxnhrua.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtekhxbsbm.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtaqnjyhol.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvyhkzak.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtfyfnipoo.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtqiohhbls.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxoktorat.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtqgumwgam.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtpqmebdcz.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfepufdst.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtdvwejibx.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtdrwankkb.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtxnhnffuk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtcpphwlem.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtrkadrith.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmguiusih.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtmtpvafin.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtnwwgunlu.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtydzsuard.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtymqvoasb.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtxulyrmpr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtirnzeffl.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtxnhyuctu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamggwqan.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtqbnyyvku.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtwozjpqeu.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtbdlbqpia.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtjlslytjw.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gteouljhjs.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtrtgmqegq.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtobeogrud.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtekaqzrfc.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtaubpwybf.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gthoumgzqy.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtgirwuqvj.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtfqihmnjt.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gttfpaxqhq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtauvmqxyg.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gthmjpyxeu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtpiwkilxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtxxgoazgp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfpvnktv.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtlvlrsfef.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtbdeajsxi.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtmmpdqgyh.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gteewdsgtm.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtftffhkqi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtmpudjrjm.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtnoihlybs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtbwsumslx.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtyshrxcaa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtsnrlunqy.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtrxntlnpv.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvpczgwp.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtzjvyjyql.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtmsvofaly.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtnvjoqjvz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtzppzvqha.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtubzqmljq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlhcafdu.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gtwvqalrvq.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtmlybhmxz.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnefdhnbf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtkbuuirqa.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtgyxwkceb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtqroyqjdt.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtonexivbv.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtznbrzrfv.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtodvyiivx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtzkrgomnd.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtqhkftckq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtxcbsjbtz.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjyeprrjv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtsjfzykrr.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtpvwxaoiq.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtibuzdaku.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtuxrlqabo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtnhdfklqb.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtxfoerxbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtgcgrjjau.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtfzbhmkks.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtnvwcjluf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtthzhopsb.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtkarbjnou.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvfrbchsd.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtxvhlmjqu.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtlhvnwavc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtpnuntnsc.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtzkzaelrk.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtpwchgcvf.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtubkqyoax.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gthwpszcel.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtxucmfhrp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtivvayfmd.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtwzvsdhdp.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtatunbvxy.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtovmdzxnk.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtwglwadsk.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gthsnrlamc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gtmhfkxebd.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtnpbapkfz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtghdmdkuw.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtmahteqts.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtortotzvh.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtcnsjgkxa.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtwvxemyik.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gthcprohlj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtllwvzfcd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxnitksd.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtkxfmmxkz.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gttjapwglw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtjkjmlcfr.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtuekybxfp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtruhmvhrw.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtfkiamdic.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtsknwxekc.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtkbawxsuv.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtcilseovo.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gthhynvqkt.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gttrwohlci.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtjvdlbdoq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtpynfiarl.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguvujknz.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtgijjumcg.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtamlbtzbp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtzxbtkoza.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtbsiszqgj.html


<!-- 参考信息 -->