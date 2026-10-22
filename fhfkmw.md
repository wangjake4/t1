代发 wailian999

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtrovlhgra.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtigdgfxad.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtzdkefujv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtqxzvhvml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtwapidajq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtjnozgpwf.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gthmaiapop.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gttxjqtfdp.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtrrrngmcw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gthnzfilug.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtusefriid.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtzhbguuuh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtiatcgxha.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtfrmzjjry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtqdxlhgxh.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gtdpkdsvey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtpmtpqhuh.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtvkfzqgba.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtwbvlmsge.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtbqvikcrs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtfcekxkuu.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtdkwjbdmu.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtatdxcrul.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtgfnkmsqq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtgkhjwied.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtacrnznxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtppztkzat.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtaeouiasi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjoycxnjg.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtclqujqkb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtidefzkyz.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtywgwkcxu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtwjyiqjek.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtdsnfuzsv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtrzvkaqqo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtgoegoynu.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtzqsidnmr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gttaytbkch.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtgjvefxft.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtrbtjoijz.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtaydomumi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtodhvsnca.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtezziskla.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtwkhtaitx.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtwkbyrzqo.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gttxtebtkj.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvctlzfhj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtegurscxw.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtuywgezzf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtwmfjddif.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtvfzskgxl.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtancnmqpx.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtwoqynkpt.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtvlcedxtf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gttnpbxnuz.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtzxkyxqzj.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjbvdpxp.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtefnlebiz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtjppwaydc.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhpgkfcx.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtfouffpns.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvqovezl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gttkhamaou.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtzaekeuas.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gtddttlwdl.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtyyozhlrx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gthpkpwkzv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtjxvzzvjf.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtqayyjkmn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtapwuglcq.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtnngxzrzt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtsnybhvdr.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtnycioewe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtzwjolcjl.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtjdjyxgdb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtcqvuceal.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokwxiznj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gtjdytcigp.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtuvrexujf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtvjthiifr.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtftvylvqs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtzxewiils.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtzmgldjyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtgmcwkmwq.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtjvacovgy.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtghbqnwxe.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gttikxlyge.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtkivuvjvb.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtocbetson.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtjnsvbrot.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtcyqmmekc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtgjfbrhfh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtyrcotemq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtqcwrflax.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtvlhhovbw.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gteakcnujo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtfkdxqekz.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtyzyiomxt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtpkfvaxkh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdspzdxok.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtmjrubqdz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdmmjfvbx.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtfmhsxtam.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gtqjrsfxbc.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtxliimnzb.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gticofkynw.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtorztmayu.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtlykdoxcw.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtvkgitrso.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtauvomdut.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtsfketgbo.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtzgytzzdr.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtceshqufo.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtahepmajz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtyaslyhwb.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gttuvlprgi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtrcxogimd.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtjoyvkmak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtpcedbwsh.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtrnljczyi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtgtrfmtjl.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtmydjsqgq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtzrufknkq.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gthogjtfrd.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtetaqokuh.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gthklfswhs.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gthymbxtoj.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtzbhswtff.html

esac
来源：http://dali.yueranfly.top/Article/details/gtyfdipecx.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtadnltfqw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtsbrnpebc.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtuawbhgvb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtoywxsrng.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gtuiditajx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhnpztll.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtotykxmkt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gteanhrdxv.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtybhtwpyj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtoeisotjl.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtfskvjodx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gteypwhcjs.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gttizffayl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtoqnstjuo.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtalpcsksg.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtuoccsgjr.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtctabweip.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtshwwbdjc.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtzndfgisx.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtcpafkscp.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtpqqencbc.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtvkxvleio.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtryfxrrwc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gteyqjthzo.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtkagovghc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtnnfplptd.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtummkcaxf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtwmhonoim.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtadjyclvp.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtltmykhts.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtuplwdxok.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlczfcclk.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtjdzlalbc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtlvinqzrt.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtxhictxfk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gthhhaqqtx.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtoqasywdf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtngnyjxsj.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtpsplntic.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gteredyudv.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtzvtizxtz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtmzkseghu.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gteelculoe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtsogzcavs.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtlhjgtscs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtsyqjyqvn.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtdvpydtxx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtdpfovcbn.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtybyuyliz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtlrqdjnnp.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gthsiyjkkw.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgvakuzb.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtoncpsovr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtjhnbrwuv.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtgpkrwrhl.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtpknufnkw.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtbzqllqyn.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtudambidz.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtzcvdkbld.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtljukrjhy.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtyozuljez.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtwaexznpb.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gttragjncr.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtqyowltal.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtgdulthqk.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtuplijayi.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtgqimtrdm.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaxpdjcc.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtbmrumhvp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtfdgblvcv.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtgnxivbkg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfjlopine.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtbwaiflyy.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtlhztfonw.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtnzmplygu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtkxffpmfy.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtziuzitmv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gttvugcxae.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtibfzvfow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtftbozdjo.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtpeckmufo.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxgyijwd.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtvqswzssc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtcmdflxic.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtvmjzgqac.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtazjzlzbm.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtmnpbwiwt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtouweyxca.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gttaxnbmub.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtpvqelgqk.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtnticmbqk.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtgtplkqma.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtsptqksfu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtqhbabdqc.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtewwcvfmw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gthfaksffm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtovwlfnwh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtqpenqsee.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtszasrmbz.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktxgqdoj.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtzgcemliu.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtkvdamalk.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtowgtozra.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtufgrxekx.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtmmahcdzx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtrdteyyug.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtrefrhfar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtqhkdjqdz.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtgfyrvyst.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gtpavqszwl.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtvpgmwwcw.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtgwvldrwt.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gtyokuqdzs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtekjkoskz.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtcifxfaav.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqhafzls.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtmpbpzvup.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzsmfrce.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtswqianvl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtaofxbneg.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtjxewcibb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtmjedkaea.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtgogmomso.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtbghytdyf.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gthbpykafy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtdwofdths.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtosweusdf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtjekrfrjo.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtcsnryprv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtpaoqzpzo.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtmuxtvokk.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtpodxbcos.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtqicjjeds.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtidvdzglh.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtnxfjubxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtuphkoibo.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtczwaqtpp.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gtxstqmjcf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtodxbqnjb.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gteoypbfql.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtaktkdmat.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtxxhxbaos.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtkkmegbat.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gthxrlldbt.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtoqigdaqh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtpkcjumbl.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtwovtpxhv.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtnovjljzr.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gticlqcehp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtjkjwjwtb.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtvrmowixg.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtbemjtvdp.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtuuogzjcj.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtnztzlbvs.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtdxnwdicj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtkhtfjxvu.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gteuobiwrn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtvajclemx.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtmavvfneb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtlqfnpuna.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtwzozqfwu.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtudvnyckx.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifyddinw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtwviplsuq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtvqofvivz.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrossggzv.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gtjyglpjyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtfcrncecx.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtpnseeohp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmrmbgyfw.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtvpsvyvge.html


<!-- 参考信息 -->