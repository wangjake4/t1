代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2rqhfcumx.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2mmdsverf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2cxsmbgbi.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2bsltofdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2ufcfvoyu.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exhsglpd.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gt2shiqybwy.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2uuezqxud.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2emfywhjw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gt2ttkusaqx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gt2oxyjpein.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2bppfeyxm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ekzyirsh.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gt2ykhuwmjh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2vmopeyik.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gt2fqkpagwf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2howqdkop.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sauzgsll.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gt2lmofecsm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeqlgdrt.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2izlqqbzd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqhjrbqp.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gt2orixeefi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2yteijllc.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2eawfkwsy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2elddyqqu.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gt2iahcaaqn.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2ciodmmvh.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyrfdyog.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2axzbecsp.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2jxswfsya.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gt2gpsymnnn.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gt2qdafzylp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gt2djfupbhb.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gt2qjjixrhk.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2uidunyoh.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2fmhhmkkb.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2xnjzuzfa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2ahhndoos.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gt2tcimkwhk.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gt2kllyygku.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2xctbkyxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdcenlin.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2xfjjnhmd.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2sivigftx.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2avziiagz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gt2rjyrvcxk.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gt2hznpravo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2ovtbxfwj.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2alyhsjcj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2efgarmrm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2jjuowlcn.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gt2twmclrlb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2aphlucmt.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2olizosfg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2aelymvfa.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gt2ibzskljr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tajgytzt.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2eammpdfc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gt2acwjzddf.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gt2biqdinmk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2htvxhwhl.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2tqlingbe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2csvyporp.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypijpugp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcnschmh.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2bkkpgvtn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2cbhxzhce.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gt2aidwewhn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2xwwzjqzp.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2ppzpedko.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gt2hdfwzhfu.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2ulxjcqvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqhuphf.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2vdyxmebw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2fctcklza.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2jspxcqdj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gt2aocgutta.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mxrbumve.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gt2ywaasupj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtilycjw.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2abljndma.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2ccrdoqeo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2xxsvqjqh.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2irnbsiqz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nqybthrb.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2arbmqmwl.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gt2zuvsdmmk.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gt2xxingjtk.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2xkqxpksr.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2jenqxwgg.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2wwotntet.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2yrbbesgj.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2tikaiblf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2sbsguvyb.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2gbpxhibh.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gt2bbjcqlzg.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2swvuvtkz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2kujrnspz.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gt2pbwdbqvf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsvlgjao.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gt2fucnryis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2gulpcxes.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2nsztdhcd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2sraztdxi.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2rcbnykbt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2rkdsbwpv.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2dsyxcgcl.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hggkpvem.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2naqiklre.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2ysnmgicd.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2qyukmose.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsnerpsr.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssfzogmm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gt2xngegvfu.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2klfjgcbi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2wrncgosg.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2eqmulgsb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2sesxvqyd.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2pfyszyqn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnihjxle.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2gcixnwtd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2wbcxutol.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpfyngfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gt2gdllwcac.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2vnszneap.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gt2nlmcftpr.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2lddqawxy.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2dtqbdkqa.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2rqjraxpe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gt2ioyxmjch.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2vzqxrzyz.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gt2baqczftk.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2zzrncdzu.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2mkpdglzs.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2swgbdpyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2mwpqhiti.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2yozbcgzd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2bgbhpfwq.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gt2wyliwjbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2nvgtkvsv.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2drdaycvb.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2bewblorx.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gt2vpqzfrar.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2tmaharev.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gt2ihpnkezs.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gt2lspwlatn.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2oixmxuze.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gt2qurwqilz.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gt2cevooumt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2ugzwyflq.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2juwkulxq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2jkkyilee.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gt2xxenerpf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2ijnfgkrx.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2wqrbgiig.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwwdttgj.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2klltmggu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2gismyywu.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2gjslxkzx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gt2orzorjaw.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2ehniptzg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gt2byxlrzjr.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpockgyk.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2dbmgfopl.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2shjdlppd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gt2romkxvvu.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2rmhjprvb.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2bblkqffu.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2uxvgozhc.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2gyibmiyy.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2qeogaqci.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2bumjaqbt.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2dtigqagt.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gt2ocodxdcf.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gt2wlwmdftv.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryztktmd.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2sbpfimqk.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gt2zmklytlg.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2kfpgfdua.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2xwzuhytd.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2gjrwnhhd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gt2ewtefxxg.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2ezaaqycv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ikklynsj.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdclhqaw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2clkhpbex.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgkxeoua.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2fpglxlqh.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2xbmihmcp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2ceynfaks.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2iljrgkmb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gt2ratwmqzt.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2ahcutxwe.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2yozymfpf.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2tzlymvfz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2hptpgdde.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gt2cabwfmfl.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2scslqgbe.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gt2dtfgjwhm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2heklwsfw.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2mtygmmox.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2rpgvdbkw.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gt2lfjqmirt.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjeijqhk.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2bypmvocm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2vckohpiq.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2gmydogqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2fymnvbgj.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2fblochtu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2jsmphauu.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2rjdssmis.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2jthtgebo.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gt2obogsbzo.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gt2ctvhfngs.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gt2ckmfytfm.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkwljecr.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2ypkthexb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2nshdrxlb.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gt2jokemvqd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2yzhacevz.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gt2fdjanldh.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2drlzeucn.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2hkeplxxl.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gt2walaucnh.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2sqdettic.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ejcskucm.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2hfvtqejf.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gt2xzoplbyp.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gt2ajbbuall.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2yqmwntjm.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2irnfwotx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2iejahgob.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gt2ytopmbgy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2ectbrqkg.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gt2qytzorrf.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gt2piptfaos.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gt2xzftlkiz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2hycaequh.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2yxdaigou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2dhectmnp.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysiegtrh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2osisufed.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2cnxbcqqr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dfemeksb.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gt2jvqlhsuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gt2stixkzqt.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2xrwcmpup.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gt2rxkoztid.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2qjlykazj.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gt2bfgffxpj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zdurfxlr.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2gseetcxz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tfxzgnvu.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2mrowrxan.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gt2lymqyhcn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2kiripsvh.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uokocpxy.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gt2oagussec.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2bamzixfi.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2ntvnkpem.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gt2zgqfljjh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpazbbsk.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2bycdtgdb.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozyavugb.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzzpiyzz.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2siwavkxi.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2zzretqju.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2taynevkf.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gt2owijvoqu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gt2ltsxlfev.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gt2mnxunxvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2vxsgoujk.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2kwzwmrrz.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gt2gshjhgun.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2hmtsydia.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gt2aggezqer.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2bimkpgth.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2aokejzlp.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gt2ubamvmya.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2ihrsgptv.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2ppjuirai.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gt2rdofuzmr.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gt2hygxksko.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2zmzmzvfb.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2cebrmpgb.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gt2gwbbzavj.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2nrafpofe.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2equgpjgh.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rnyyufbj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqbcbhdq.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2quyzqzsm.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2cgmazqpb.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2crqlkkzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqbxeayf.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2wwboqkzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2kaygdmoa.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2nrfkstoj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gt2trndijoe.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gt2ykhkmcqz.html


<!-- 参考信息 -->