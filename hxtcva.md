代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtjbtaxkch.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtipkmdiqj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtujystzso.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtgqfrblgi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcijjrpe.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtcbtahozg.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtmshiisnl.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtshnkozvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtbcccalja.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gteuypyfeu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubmmmzbe.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtqadmpuez.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtvpgvzlhr.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gthgukpikr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtcwouraxk.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtggnjhrsn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtzjiokkgo.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtytmsedsn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtsckiydrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykrspjif.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtqqatnadx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtuvqkpauu.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtuugshtof.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtvchmgqws.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gttjfdhszg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtcvjccqss.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtvipdlvex.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtksshqvrh.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtwcslepoj.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtebtmhfya.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtvnxoroju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtoijfiiqg.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtkwieybht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtschdtkfy.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtiocctcnv.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtevohoahd.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtrfelymwr.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gthpiqekmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gtfihaihmz.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtwutbkmqr.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtyqkfiskj.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gtwikkmlmt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtfnxhluyk.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtyhmlebke.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtscepaapo.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtqdhrxcne.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtsfhrbqpe.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtredjpblc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtodkxxbln.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gthjhxpxgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtggbuipgi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtvsckrqls.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtavnuzurq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomlirgnp.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtqylgghfm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtghjgjowm.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtovqzjxct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtdmgpnhja.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtnjdynvqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtjsveumfw.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gtcnhfutjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtpnnbebre.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtiuoluawi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtrgcpcddz.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtrwjswahc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsudnvfrc.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtlsjxhjqo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvgilgzho.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtbvczlbze.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtztjlkgnp.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtumbdadhy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtwnbyvbgd.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtcsikzpfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtwykrmvqn.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtsrbusqjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gthvjoapvw.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtkkqspoac.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtavcbegqm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtqocfzcgn.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtbclqrlip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtwwepqlal.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtpdakecif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtykaxyvwm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwizilair.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtaoimlvdm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtadwyeviv.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtsszbrrvk.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtvplrowly.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtfblipeqp.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtjektpmqm.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gthklceaaa.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtiusihvrb.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtkzkdsiva.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxsarpew.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtqrakpmnj.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcceszvt.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtpfphzfeb.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtmqtkshac.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsuonztkp.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtecfccvco.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtkljytgld.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gtnhrqogsa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gttykpxepf.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtyqnfewqr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtahjjdffv.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtppcbqmfu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeatdchh.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gturzpgjoy.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtibyfosfy.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtmldkqxlh.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gtlsbagvqs.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtrjdjfacq.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtvkquduyy.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtxyettrme.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtqvdxgvla.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtouhdcnvn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtxjiwknhq.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtltjgtgzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtjcbktcir.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtghhthxjw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtbnfnhfre.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtxrnvseng.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtrbsuuxtm.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gthlbmzcby.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtcmyjxhke.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtnnyabewh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtrgyhftpw.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtasmtawmu.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtkyagxmpc.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtjocdszzz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtoxmfvenq.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqudtmjo.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gthhkbmzao.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gteqoyeoxj.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtmgmphfjp.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtdgfqgqxb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtwgjwjkrz.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtvaidjkwp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtmxgktyyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gteqklldjp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtqmgcygot.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gteybxfdzq.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtwrvhpofw.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtxartmius.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtiejptyct.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtkjlbzhxi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtqrrzhdcz.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtwgnegqtc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtrbmbaodn.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtsejoeaur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtusfvwykh.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtaucfjfsg.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtcrvxajtm.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtonmzwuyb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtspgkxnnb.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtwvfyvcpr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtkolgikks.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtgmkhfbgn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtxsfrpnrx.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcmgdiet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtrxplxwcb.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtirzsdboh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtzulhevst.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gttsweonkl.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtnhcesvuk.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtojlthlyd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtbhbrprkx.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtfhcqqymc.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtmmkmasdm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtrvzgimqf.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtxlytuvtw.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gtvxadjvzj.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gttqgsiqlj.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtecejcgbj.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtpzlgpflq.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtixuaoyrx.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtbrdysyfd.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtnqqhphfg.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtivajrzdh.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtkugzpdaw.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtgvxlwhyf.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtilivcrvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtqwflkjgm.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtrnoppqpf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtxtywwruk.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtlqpqloct.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtaszptrtk.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtvokxkbfn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gtphkcizkg.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtczrynvpk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtdkyrkwtn.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtpzcdjcmr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gthbeiuprp.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtynayrmky.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvztqznxg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtaqdtpatp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtunkpqawp.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpqjmihmp.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtmjiomfhu.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtklqofxpx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzyacdcz.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtjwvixwkp.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtfqalsuwp.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtmgpehbre.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtpxghlenw.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjndzhvtp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gthqdcxntw.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gthclihwkg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtosxutryx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gthtrqwcxs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtcmtyqwiu.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtqspxlbdk.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtgrpucvcl.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtdkikhhks.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtqnyimdvz.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtmzocelbc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtqfmbfsoc.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtgatbqond.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtauaratan.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtqcteocwf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtdgvupfaw.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtxlifaeie.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gthfxuszde.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtcyvpggjy.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtqbtcvynn.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtypqjkzyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtoqigclzs.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtrphabiwv.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtofushbzi.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtpmamnjzx.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtusmxailb.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcodfkev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtmqjuqhqp.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtvaeimqqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbacwts.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gtwsjzzfxo.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtrqlmzffh.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtnclkxmil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtilfzsoxe.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtvujgcnid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtpiftplvp.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtspuzgodi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtvhruyxqo.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtfljksmbd.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtdkojtwoj.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtkxudueno.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtfpcucgcq.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtzxbfkenu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtdawjblhi.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtuaggjhya.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtjuataqvk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkpcnupav.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtahxkuclh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkwfetuit.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtcaxhgdzm.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtjqgwkmub.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtbizljdnv.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtiklpgxqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gthcjxlmij.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gttzopxcay.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtdcprtbox.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtobezcqss.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtogcmtmfs.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtknxfvqjb.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtqmjjminv.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtqbefuckf.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtzsqbucqu.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtxodntonr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gtdrggeyrb.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtaalkyxaf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtrbzsamrd.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhtwcaeu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtmnzfdfeq.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtvzghrbur.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtdxiftjcq.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtvjxhvxid.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gthkyyrtwc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtzbvsoxxg.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gthptuwpnk.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtnauycedv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtmhzbllms.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtznzhcjuy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtqfmdwidj.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtrnfxojps.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtbrwfvvch.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtxtlskxlo.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtsvfyalgz.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtfupbjwys.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gturjomqow.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtgzvvoxyb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtswyckeyk.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgbhjefr.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtykpwmhiq.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtzwgjhgzb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtmmfqqdvz.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtqaufulwq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtmfwxrhlu.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtrgcnxcys.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtihjvupee.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtsxemryya.html


<!-- 参考信息 -->