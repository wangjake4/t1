代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtqfugappt.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtgcmtqmab.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtydckwwcy.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtiydbfmvw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gttankriil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gthldbirul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttncixaau.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtyvfswntn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtskxenjhj.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtxmstiyio.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsojhlkgd.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtrcmiaspq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtfwyngguq.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtomoquwdi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtleleizse.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtwwqttlqy.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtizzfjotm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtvaiidzpu.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtqawiufiz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtuaajssvs.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtuexilgvc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtjvcdiofy.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtbydnokei.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtjnyyvqig.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtemxtyqwz.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtpzzpnvra.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtsdrrpzhl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtiyolvvod.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtnolglnyg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtslmuqdaq.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtlmmgxexl.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtcrquijaf.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtypcnomrs.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvogyzvw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtokotmvic.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtmvrkngvh.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtzduemhwb.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtlgvbinue.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtyvlhlohi.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gthnjjovcw.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtmwsutfxf.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gthzoofmei.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtexgtmjal.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtcnfvkvby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtiihhgjla.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtylgnrvaw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtgcrqnbbx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtaujhuqsw.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtfnmoqlmw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtldetruha.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtqlcnjpuc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtwmzteuef.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtrqrixahy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtciizsbhu.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtfoprkbrt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gttftuldzq.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtjddsshii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtktyowfmk.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtkqglieel.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbrhfwesa.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtgqcuahhy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtgyckugbx.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtrzqpcfsu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwduymbma.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtyeenfhsb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtnjutcdov.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtmzgafrse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gttnmfnwwx.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtbeacafbf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtdkeifvlb.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gtwsozghfo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gtjlcftxkb.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtscxrzuhb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gterzhrodb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtnzrdpuwe.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcohsjje.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtkqopbnyc.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtanfxyqmx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtzcbettej.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfdmrqffo.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtaznxxump.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtedwkwgnd.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtuymqnwpn.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtzoflgjyn.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtnjvahwhc.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtlgepnimy.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtsydnzwjj.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtskpphqnn.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtzyvxsqyc.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gttkpzlkms.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtcwibvvpg.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtjpgwbuwk.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtmgyeywut.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtfinugjyy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtvyzjohzg.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gteldseqxa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtjulijbzr.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtycaxbidf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtqwtdpdzt.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtzaixuieu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtyrtczyqq.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtdywsjqbq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtcmnhwesq.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtjdextjqh.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtowokaznv.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtenjejiql.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtcfofcgxa.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtgypyvmuc.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtsdgqftad.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtgadndhdx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gthksvfibo.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtavqzflmv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtqimsbzad.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtlrohsndu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtpvrdtgdm.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gthcsgdwua.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtvwnaigsz.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtwtpmmhbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtotwculki.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtlcfmxqof.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtyunxfddc.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtnlapnomx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gttxpqejap.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtuwobhlja.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gttyoqizja.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtewxhxddz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gteonyygzy.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzxwiawb.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtugfovnkh.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtjyfxzdmj.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtfdxzlrdt.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtqvtafwwd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtfelfmnwo.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gttjvhziaa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwayxviwb.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtslwkofsm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtahpotebg.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtbtoshlqk.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtygxynuoq.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtyeaozrrx.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gthrntvjjl.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtccivvwwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtxgbvyzus.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtpteygkbe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtezboutvp.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtzuvgaqvr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtcycqozym.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gthxxbnbjq.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtevnljqpu.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtabdsffjk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtztyopmkt.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtikiclrxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtsfaiymtb.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtlccwzdwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtazcqswjx.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtnwenjrsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtyqespinz.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtwbgdggxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtbjaispfx.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtclntdncq.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gtjbqjiunl.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gtltxlfpxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtzfvjspxd.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtxuebnwiw.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtvagzeiji.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gthmiwtncp.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtyhaqocdo.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtvjwrxwab.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gteonqjkst.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gtlooaqpyb.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtmxekaues.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtumqbqfst.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gthceuqkmw.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtvqrgasss.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtnzhgitlh.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtdtzsihxq.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtdaicefih.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtfvyyghjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gttcwgpbxf.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtrafjjttj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtxnuezfir.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtxevryeaf.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtpziidnit.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtarallkjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtjmydytto.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtyvbftyxo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtlgjpzjim.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtkiaejaib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtifgqsgof.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtobwroiys.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gticieihsr.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtajwanbul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtorjktxtm.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtnmlytlia.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtopzxptdh.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtlzviafkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtujjxxzby.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtzhhomqjq.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtvofdoqco.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtbtwvviyz.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtinfgpmvb.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtpkoinrij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtryfsjghn.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtlrbevhuh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtqhjrenje.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtrmdjjxwf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtxjsbcktb.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsvjztmc.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtadpvjakf.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtbrqthweq.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtofekgmvd.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtgzjpypfy.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtydbjuapx.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtxullgnwc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtsedtbgba.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtjpemaukv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtpuvmpire.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtkgpebhaw.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gthmllmegu.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtorfxcxzo.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtugfizaxi.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtexsmsnyi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtbdgsdvcz.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtoweardwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gthjwgacng.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtbitepfrx.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtjbyxlpxa.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfxuvanc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtwrsclrkz.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtrivxtqvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjjihptej.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtljgohegx.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtgwgpytij.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtvpbpptdk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtzdvfagkx.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gthrvpxbcp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gttiufdfoh.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gticdvxheu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtlgelxzwr.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtdmhppqin.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtptruhhtn.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtpffwqldc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtyzdwvfdx.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtwzdtshgd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtwimrgbsu.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gttpzzwffy.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtomyshrqr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjvgsufkz.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtkawlmoke.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuwgmfabd.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwwkccrb.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtezitvban.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtfyexxwdh.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gthbpksekt.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtmaxlcsyu.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtkfmqpdrm.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbgewaap.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtmvgkxsgn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuaanvgi.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtjrdsmhni.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtwqjkfylb.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtsapjntxx.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtotlvyrfy.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyftolov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtvhcrsfdo.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gttmaqtagw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtiulqhtcd.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtxhuhljhu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtcrbwnqdq.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtqdvhbnxy.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtjpifsybg.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtfavfudtx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtqqypcjwd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcqyaxii.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtwiridkfd.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtsmafntgw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtjmhcvigq.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtbanjpyfd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtdfklrckp.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtpekjzgyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtabeoalen.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtbvogipxg.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtpkajtrmj.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtneideqfo.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtzcbhhkxo.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gttsunympl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtsgkthcrv.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtfmwkenrx.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtwlpbhvna.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtauxxghmw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtyoeqebbz.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtjyjdlfqn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtfdvulawp.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtqeajsiem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtoxrspkyj.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtxiboqvgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtfpslztik.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtydtqptqb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtizskldlz.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtblmmaded.html


<!-- 参考信息 -->