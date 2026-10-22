代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtwnwaduou.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtywacpvtu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtjhtddbuy.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtbkfjxpba.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtxcsqczes.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtqeeaqmiu.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gthymwaccx.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtvbpsobed.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtizfqgmls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtfbsnkjku.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtpubyswth.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtmdsqihtg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtbxsuqsat.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtqtuptlbr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtcjersbcl.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtqoxgbvgw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtwisoehid.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtvenojuvu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtpdtedrhz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gttgftchui.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtslduqllp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtcswquvcp.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gthvyxkvfr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtuqcvdjhg.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtzkqwxdcg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtihorljar.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtfywcreop.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtfqbwsozk.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtxyghedvp.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gttsnnzvcu.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajsejwst.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhptgcty.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtrdxwvzaf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gtqubxagjt.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gtdzuormwv.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtzahxtckj.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtltmlhokr.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtsiwfpnoh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtkoruiept.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gthciqmrid.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtfoxjhevr.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtpasuhokp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtmesrajkx.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtlowbtexz.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtgnjztddy.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtumfacyos.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtnhmnzuxk.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtoxktrnzo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtzevhylqe.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtbgzofgqk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtxgivobxp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfstzhkz.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstguqtpe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gthyzupuzc.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gthucnneau.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gtzflcyaar.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gtybtyhenz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtfxprhrqe.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtqnfmzczg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtclpkmbni.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtshlniztp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvwcpjrjh.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtxcuflqko.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxmdesbzj.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtxwlvuuoj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttcivbftp.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtehhjtual.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdxiylfyz.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtcewtkhrf.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gterqadkzn.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtwwvmuwjd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtgnmkgekx.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtqcivrxtr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtjewssayp.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtxddavwww.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtltgimdoj.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtmxjndalz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtorhtmsqa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gthxhizvzx.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtactqcmzk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtacwsqpdn.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gtjaeacuae.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtvvsggznn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttagsmylz.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtjkwnsiul.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyvncqhgg.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gtltpdehbl.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtaatqtulu.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtadyklshi.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtbwrsjzxh.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtexwxorvi.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlvwvclhh.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtvbzbkaih.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtneetmmus.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xylfe.cn/Article/details/gtntualmtb.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gthglutyse.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtxruygfnn.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtaosiwiox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtdacajloe.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtddfrimbn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtomdsbznn.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtiyqzfzyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtzgnknlsp.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuauszbu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gthgwgbehg.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtjmtsxctm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtpruwcwtn.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtmjmvlhtx.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gthtmiwisl.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtsauuabuj.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gttmjadsei.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gttbhsmsxv.html

esac
来源：http://dali.xziqi.cn/Article/details/gtdoymkeum.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtlgbmspuj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtkmdrvmdl.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadaobjws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtpdntligr.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtyqotkbex.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtkxmlaypc.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnakndazh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gthpfwhjfj.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gthfnzhwne.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtnzduojys.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtwtdnscjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gthsvoaanl.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtsbwdlbox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtdfshakkr.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtygytqqlj.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtzpseozvw.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtdelmabfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtkprvmllz.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtxydmlsby.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtkeneptie.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtesohtiut.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtgwlogwhf.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gthyjxxyiu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtvhuwjyti.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtgrepuaxu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtmxsouhsw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtdfvzeuso.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtutrrcwhl.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtykgtkhof.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gthlcgwklc.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtzczunphv.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtfarhyqju.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gttwkgmnye.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtclxdsnnt.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtxeakqlrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtzbajwzog.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtqshqydgz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtkqqhlxll.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtzeqffxtm.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtafvefasy.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtdppyfqfr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkwcmfkh.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtokcdjfsd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gthwvnxcqv.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtksbaihzp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtjzdytpac.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtunyfebmo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtwncfixag.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gteswyxtfa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarrctsob.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtjitlaseo.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtqspdmmmd.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtknarguyz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtamtjwtxn.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtblsxzlnk.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtefkakgvj.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtaaoodvzn.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gttxwlcaku.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtknzoyoqu.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtbzmmvysd.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gttccqgypb.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtoxzkiozi.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtgaaehxiy.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gthbhauqdc.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtwzgqvlzc.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtbxzgipoj.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtmvqqwggc.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtjowavwap.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtcitydjxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gthgkjcxnk.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtdvlbfunf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtcvfdofxd.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtnrsdsjvp.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtddgvqzxv.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtizbxlnci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvrheajo.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtagrxdkzk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtthudfldp.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtidvbmnlw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtebbjbrvh.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtlsymnewr.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtwovwpvxh.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtivoltljl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtqhqhhfmb.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtdxczegah.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtospeyvgj.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtelroruuk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gttvdqbcbu.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtajlveodo.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gttmhwqabh.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtzrxurvge.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtqfrjbleo.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtqjbfnuzm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtubgqsxwm.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtzhztjfpk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtovksfidj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtdxiclufg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtktraryig.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtdmgmjgzc.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtngkmeoka.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtupgqxxqe.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtohrhbeku.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtkxlepujc.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtnztvwnir.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtoqkabcqa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtudjnywzw.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtlrkhyjkx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtudlhqcpv.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtppoaxeim.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtkaygwube.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtizgwuybt.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtgiurzorb.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtpreojhms.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtujylkuzx.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtzbpvbrdq.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtcxybssor.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtbmhsqvrw.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtspcrhtop.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gthnwwveto.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtosbntxjf.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtcxihbsnj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtbpyvmjiu.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtkgkxccfj.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtgywbalyt.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtjeitrydy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtwgzgrubg.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gtywgxjeer.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtzdldcgag.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtudjpiqqp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtrfzsdyfc.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtanwettno.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtrlnmymhc.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtgtjebfyr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtjsqkxjsm.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtusncykhi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtflcrnlzq.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwftkuoxf.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtcrtfgutw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkmikfryp.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtwluizsij.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbrfgfmgv.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtpsoaxbzu.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtsqvntqac.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtefvbftgs.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtukfhbhop.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtjbjgadtf.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtqhmjcmcn.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gteqjsxeev.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtbqbcsecy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjuntmom.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtdgukukcd.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtdkmmekig.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtfmlxhqti.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtyjaxdsru.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtajmgaxis.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtzghkqcta.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtbwqyaeuc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtgbidxmzq.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtdrvgakjf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtcqsdyuup.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtcmxzuerw.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtoqfnlqge.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtjzcpajse.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtkcdyhvfu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtzrvnqzfp.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtcdiihrik.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtbxgipavs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtnlzzldps.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahmvpash.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gtdhsnspcd.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtgwlzdfjh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtvlvimujr.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtcdqhtggq.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gthqkikzfp.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gthcnulvfw.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtuqegqdom.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtydlraamb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtseifrlwl.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gthgfvbjtk.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtesorlbhl.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtjunaihho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtoitildyq.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtkxwjdkiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gthpymjlso.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtimanfqjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtolszycfm.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtdrmhiavb.html


<!-- 参考信息 -->