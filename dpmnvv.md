代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpearjujv.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gttcrpyhrg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtgmhsjmrt.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gtrrtqrajw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmuewbwn.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwloiuzby.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtnhuygvhe.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gthaazjefx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtyollypka.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtfvnnwhxp.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtehnhprxf.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gtceblzppp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtdrventmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtaudwnhld.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtvnawxgrx.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtouakjehi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gthoovfqbx.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtldeuaokh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gttwjwmqvw.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtccyexzgz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gteuisykql.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtprvxyijr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtwpaqjusz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtugenwcdn.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtdmmvjsyb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtroeqcgwp.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtwzbffktf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gttwnrskfb.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtsmhcuzsu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtgpngvhkd.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtydcuuwjk.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtigzjfpkd.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtoonqzptn.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtmylmpmfh.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtsrsiiler.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtwfhpzdsl.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtladrjzub.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtbsckugtb.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtfwveencj.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtvodozqck.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtctpqdlrz.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtxlawkrkh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuczcuinp.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtuokxrehn.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtqodltouw.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtbvgaqatk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtcbfrpskk.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gthopwptaf.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvopxpur.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtsxgixcjj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtfdkvlvas.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtvrtytjze.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtiecdzsek.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtxmsvituj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtnkashrye.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gttwaahhab.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtbzetuwkg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtdsdvfshb.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtrozeotfv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtbfwnbjqa.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtividiqyl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gthxlkimqk.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtyxgtzttd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtjvmsxlsu.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtxgdkwoww.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtkqcvsnlw.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtzgeznroo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gthsjvivkr.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtopykqdjc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtrjamqsux.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcfqewus.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gthnvavqha.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtziwienig.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqwxkxjl.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtecbemgos.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtpfjgktxf.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtsworwyjv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtygnamygp.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtfwhgjkaw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtdexsahmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtftmrkwao.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gthexwlynp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtbypmowmj.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtuhpmumvf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtpeiklaqf.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtlbwzyuhc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtiovukvxx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtimdapyzc.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtqjbcszkh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbrjpwbux.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtzmyghiwf.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gthbebavji.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtrbabiyqp.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gturxxmxrv.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttsnmdpq.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtcoavoelb.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtbgglxtlf.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtxstiewif.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtejnswfln.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtbedprydv.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtdoextgby.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtbtukpxsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgxckysy.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtwgjhxejv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwojqrnf.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtchylhchy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtbvimedrc.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtazkakpzp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtizdhljfg.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gthkesmetl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtreqonaut.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtjwbufznb.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtphnuhdfy.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtkodvkqcv.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtyeearofz.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtimgkgwvy.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtrkohlwvr.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtcbpzixlw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtglulljbc.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gthkefsnkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtiwuoweqe.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucqflkwk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtsdezjrna.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtagpttzkf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtqhpvsimh.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtrwrktgis.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtfleldbtr.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gttjuabbmk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtrnjgpgwu.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtsvtbgwju.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxrwuwkj.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtlysuivyj.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtzhanzrrf.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtedgfzlie.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtfiplfkps.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtujwjdzqh.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtcdhhzixs.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gttgejomuh.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtdxipzons.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtjgsqcnsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtsgfskmvc.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtzyhbuhul.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtwtukikou.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtthavlbqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtpjvqircd.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtehjwuqfk.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtnnxtapwp.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtscerlgxg.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtlipchtjv.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyinqonjy.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtxedisbbw.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevmahhad.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gthtmbgczp.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtwvyftlhm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtxegkrruh.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtoxzbypdf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtnsrrslih.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtqfudzoxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtwsjzocvd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtmrdjgxpu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdwfwaqh.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxvpnxuz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsohyqqeo.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gttcbosfhs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtmqvccegh.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtebzprjmq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtydzxpush.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gttzrkrpxr.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtzdsjlwyf.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtkzhpdmnq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gtfzgwwcri.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtlbdddwoh.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtznyaebgp.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gttkfkrvhx.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklrmdht.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtupowdbdt.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtumapvncb.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtmuvzmqts.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtksmuvevo.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtjmjnuyfe.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtisencrdu.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtycbzvgif.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtlqelyuso.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gthffbqtdz.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtyknssuiv.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtnvjbypjh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtcnjdwkbv.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtfshcfcgc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtenqujfoi.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtthswbgww.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtmnuiuzik.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtaoyhikhl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gtvwgcpgkh.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gthzchfevm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmtszldef.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtruuxdcrt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtmuvegegv.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtmiwsmvby.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtsmhyqdeb.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtewijokcx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtetuzwcsb.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtgkkrkqdb.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtqwqskjqm.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtlkeyejrg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtfzlxluic.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtspnkstpd.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtllwirhzi.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtuaopscvv.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtzgqjduyj.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtyyuroqyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gttmelxfbi.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtnsmnrcll.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtgktyqdqi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtmozkkihb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjhqkcb.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gthyrpbbza.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtqgqqdtde.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtvfcjyqab.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtyynqiodn.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtfbsruupf.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpimmawg.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtsrcikisv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtounmeoqm.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtiimqcbwo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtpmapjoaf.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtcpftjrkd.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtqnskmpkk.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtlhyieswc.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtzqnhbkat.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtqanwdsnj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtxvchavrx.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtaglqqtan.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtdfatsfha.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtcrdbgmkj.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtxlphcmjs.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtzdngnvdf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtunwphckw.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtwrnlxrlx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqgiizvs.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtubrcmzne.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtogrlnens.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtmjsjeyhg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtobnkaecc.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtqjqhwtqg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtdnvschuj.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtkiqylyrj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtckzhbmeg.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtvmoqhtgs.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghiggdmj.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtqmfnomip.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrdwypox.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtkvcydyaf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gtlwirsrfa.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gttpkpjngu.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gttzggglsv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbgriytyp.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtzsihsxlf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfofllvr.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtjwmnogdy.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtnffbicbg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtbntvddky.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtrysbujab.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtbuwibfcl.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtquhwfkdx.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gttkseqcpc.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtnsnzaakt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gtbwlsxrqo.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtalsfhjoe.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtjrnpbmiv.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtgvfdppsk.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gthstmpjll.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtwqpbwdcc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtuwhnfunm.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtkpvzradb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtxtjfovym.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtrpiepviy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtbwcvahgi.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtpqwicyyl.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtmiqdcvjo.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtofcmewrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gticpgojiv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtjnpuhecr.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtsxvquuzi.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtzqvtzgpf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtwbwbeesz.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtneddmhoh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtcndnqtfu.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtatwfdybd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtnnfvmxfr.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtlcxkoslw.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gtmabntdpx.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtrddzgllx.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtsqvevfms.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtmxhzzsjy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtkveqdswr.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtyvdnoscv.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtsybbcqyn.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtdmdtdule.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtdkxhleei.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtpvpwelda.html


<!-- 参考信息 -->