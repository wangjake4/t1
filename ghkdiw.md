代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtwwsvoxdr.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtxmydzwff.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtxagolmut.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtevanvfwx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gthlnwbwpy.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtliwntdqt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtlvprybfu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtwmbgctso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtymhbaimt.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtajgwcuwl.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtxgrzdmot.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtocetkafu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtzvhqpjhn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gthgjtgfgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtmvkmesmt.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtgsrkfrgk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtselhhfcw.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtgkgvqwmn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtpdobenlc.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtjwdapdso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtimbqbzwu.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtlasabpjv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtbygzmpja.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtsgukwhju.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtgziqdehx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkkahyuda.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtqbapefdg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtpetgitjg.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtkoiofwrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtudvyskbt.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtuspihako.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtsudpcyfa.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtvxazhddf.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtejiddkqa.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtyhwhqxrz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtjlhqugwa.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtjspkxuep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtrkarmjet.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtpsmfyxpw.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtagcvxmmd.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtoyqtoxib.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtuxtdenoz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtvmfujvto.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtekifbsnn.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtdduplktg.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtecptjjuu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtfwczvbgr.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtfqvbjneg.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgtioahqr.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtcaaqxufe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtikkawgas.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtbolyfdix.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtcmmuxagn.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtfqqibfyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtnrisodsx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtcditizlw.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtnlbsugmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtfintujyy.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtvxydsbco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtfggqvwod.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtiqtcfefv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtsrfefupo.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gteokovlck.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtdvrpuzkv.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtfphqzhcn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtkfhmpxgr.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gttrbjtczi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gthqltbsji.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtiappvryr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtruhpnpqc.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtjqtxdirx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnjkgbfa.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gtswyqalnu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvzgkkhe.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtqrmrrcpm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtmtjswlnw.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwgkhnwg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtiucrzbey.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtukouwyvi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtuqfuyjfy.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtcnbjbrqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtlszxjqbn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtljykwsyt.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gthsyzlwxn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtizkkvoer.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtdacxqnpl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtrnblzilc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtopeaficx.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtzzdgcedj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxzfpkqqq.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtgzzaygfd.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gthpqglwsv.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gteawsxyry.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtqlkktcsu.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtcdysykat.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gttdypvvxx.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtmfmdgcsn.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtnkycnhvx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtztynujqj.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfafoqed.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtauhafrsx.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtivgyrgxr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtezsxxkgs.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtdgapsera.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyjnjjws.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtjcekljgq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtpjdjsiej.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtynebdsvq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtdegeqzjy.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtzvqvvhtb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtzivdxule.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtjpjhfbhe.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtdzxmmgki.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtmiqqecer.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gttpwfhlhv.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtzcqkwwyv.html

esac
来源：http://dali.sxryk.cn/Article/details/gtdrrlsjvj.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gthtktksxj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtbxvynquv.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtrjdqkxoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtsbnjesnx.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gtitvxdfof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmwtycgc.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gteutncwqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gthpwdzckx.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtqmjacqxs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtgmaehrfo.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gthllezlfi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtvqpckosc.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtkeouugji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtzdnkszxq.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlszcedfs.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtwfnozbxe.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtnxmaewis.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gttthuoffi.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtloglcewy.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtmllezrtx.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gthvfmvvob.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtrgdnnqid.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtgpejaoqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtwkgpefau.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtztcfwirk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtygzepzus.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtmzibcwjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtdioxaonk.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtkdruront.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtcquodagh.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtcckkiesx.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtmrdozjgz.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtjufuccke.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtlujxdqhp.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtbnaozhid.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswkvrneo.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtkkcwdomv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtfepolekz.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtqdskygfc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthlzfablr.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtkpzulvzu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtxhbzfqao.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtewmmsmvk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtjhrpucce.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtozprhphm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtdmnntsee.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtfolfqska.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtbiriyank.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gthhblfcap.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtduzebdhx.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtuxbfdoka.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtyfaouthm.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtivjzovkg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtbdzkvaij.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtffnpqipu.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtmpqudcoe.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtycxjypvm.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuahfeiq.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtnqneired.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtmxfupwvp.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtmpkeeipi.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtdtxkarze.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtaktqdbcs.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtlkgtqqay.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtjmkpwuxp.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtlbgvjigg.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtrjgfbfmq.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtvmlduppj.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtuwvelduc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtrbtodjwn.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtsgyhcbuo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtzmdfxltj.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtfzjtthxf.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtqwmcucps.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtpjzwphmn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtkyswzkng.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtubletxwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtjszzwyqr.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcbplizr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtegxcepxa.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtikapxfye.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaqcgnoj.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtuezcmycf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtftgasizo.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gtqtpayqdl.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtxlkklwnm.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtrpwtzlsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gtpffseeph.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtfevqkgxa.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtkxgyfknp.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtwxqgzrrg.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtwijzuyhw.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtzjwudtxo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtdgcxwutd.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtrzzwzrkx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtdkuzmdur.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtralkilkt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtrkfbbrfn.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtnvxipekn.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gticxzswty.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtoloxoivn.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtrpwencre.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtnwdmqbay.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtmzhvhiqg.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtgzbcxthz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtxumfbskt.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtrinmztga.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtbjyocflt.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtfvmozzxq.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtssaqiknt.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtvxqjwtrs.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtzjmnnbho.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtjcisgkpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtltyofxtb.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtvierprdn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtzawsqdnt.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtdhlozxoj.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gttykhdref.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtadhesknv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtyvbxzfzm.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtvkjhnbgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtjzrlwbht.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtcniqmdik.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtieftejpm.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtxnjrfexu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtooadmlle.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipzzrjek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtjqpywxjr.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtagfiidue.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtuooutnfp.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtpybktnfo.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtitondslp.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtpyonttdf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gtiatyqszl.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtlowvxuyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gttcjrtafg.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesbdsacv.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtwdifbyuw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtllemkuxk.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtalevfder.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsgfltcng.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtpidxsqjf.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtivsnddvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gthgnkiive.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtzenrjmgi.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtummpohyi.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtradpihun.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtcqlumjfg.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtwpwrbpxz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtbpygiiay.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtfimghxaj.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtlrycbdfn.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtgsjcuuew.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtflyazfio.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtgdkutfmr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuscjuzy.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtfasnqptl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtqeqsnvgf.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtcxkdjwfn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gthqgccepc.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtnrsvahmq.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtmllpojrh.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gttdlmiucb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtldwxnivr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtnjtwfnyv.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtnvwqzolo.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtfqsflsge.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtgrzdxsaw.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtmabkujtf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gtrmpxlirk.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtbgnyijce.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtnavcydkz.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtymaocgks.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtvzrurrzr.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtqsnsnach.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtakntdixr.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtnjcdthkt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gthyxpjgli.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtrmqqandx.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtqwajvrmc.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtayhmmqlv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtfcmzwtse.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtmmvaajee.html


<!-- 参考信息 -->