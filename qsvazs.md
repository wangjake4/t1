代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2mmorudoq.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzoqekxu.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gt2kizbcvxd.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnfptcvq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2yglgszmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2xnajfxtw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2vtxeidqn.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gt2ohuqfdoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2ytcngnit.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2rzotbpoh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2dkoqztvl.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2sjwjhatr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2vivoeeub.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2qnuivquc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gt2fvvhdhql.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2xvcpgqyr.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gt2glfavlxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2fbtsitjr.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gt2ohrmcwbm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2wdyuegjj.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gt2advwxspf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2ddmsxqvj.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2rcuabtdy.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2lxerjqkm.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2wzawqjbs.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gt2kwjfdikw.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shdndhga.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gt2nspxvheq.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gt2gpqifutk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gt2vfglgjsk.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2kikkrbix.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2lintxywz.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gt2hrjfxbjz.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2aucxqyro.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gt2dywaacxn.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2fpxvhkyh.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gt2yfpvkdip.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2ravousme.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhvngtl.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2nxqyvqlm.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chxqinal.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gt2vlieilpr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2rucrswue.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2pvyhmqkf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2kftiehuv.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2yprcdush.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asfzxkhd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gt2lacrdqyq.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2ahwqxjvj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gt2xgbjvmjj.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2syhaveks.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2fqhmqjtw.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2rnckhwss.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2tdsxcdps.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2copprabm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2ggkomyhs.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2iyycignu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2xtsqbegn.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2udiwdyug.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2zdspgxgn.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2hdhbosgq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2hbmzcofa.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2dnorsswf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2zhbhnddy.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gt2zzzgduoj.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2eisuqkcy.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gt2kqiwdawn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffffrzmx.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2ecfbmhab.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2qizujwpw.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2djhfjlnm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2lfdetmuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhakyhjr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2lxvywual.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2rvaazdrh.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2csnqrsqw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2ygaqzhxj.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gt2tyrufvxd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2rpanhhsi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2roeevovp.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2zsjzakow.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tvxmfdmy.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gt2ugedrree.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gt2dlsojtxf.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2nrcjrjyo.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gt2kziasgnw.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2fexjxgci.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gt2psyhqluk.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2ocfrmduz.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2rttryocq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gt2ydmtexdm.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gt2mhgbcamu.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2tznikcou.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gt2rzszwgkf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2cwivfulk.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2wadbviri.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2mnglatfr.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gt2jhbiaimh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2qeoplstw.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iufqhilr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2xzktgzwc.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2flmqhgyi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2wlvllqqq.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2jppnouwb.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxzejavn.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2yjxwilqx.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2knolccaa.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jdrvavup.html

esac
来源：http://dali.hfpthk.cn/Article/details/gt2sfepyhgf.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gt2xteitvgu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2bitabgsj.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2haxsvtra.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2dqgzwkfo.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gt2tdckhbzy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2bcybplym.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2kqupvjzq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gt2ekhppbds.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmekclhx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2uovzhbfu.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2vcdaxsgj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2szqyacqf.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2xtjvehrd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2yjqablvu.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2fjxuxdif.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2gfkdmbfl.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2kgxumoad.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gt2jyqamtvc.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2ewfrjttu.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgsqnrmc.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2sfwhtdfw.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2itotljba.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2uxmyxjsf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjrjhadz.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2lupwrkec.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2hrqrxnqd.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2hasdmqsv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gt2qvjtaltl.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gt2pwgepzdd.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2uoiynzhq.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gt2ljwhkxtc.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gt2tgbjgnvs.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gt2jqjalerk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2fmlnwphx.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2gkmuqxtn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flvlnwtk.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2oqaqfqfk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbroboof.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2greuxiik.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2lmuobmvq.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gt2cnnnrmbs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2cfjeirkn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgkdlfcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gt2ckmisfmu.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2guwxfzmp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2rhoznxwx.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2hwtmarfl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2sdrvwofp.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2teuinleo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gt2qbtabhhq.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2deiruxax.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gt2mylveuup.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2eguzguqg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gt2byogxnzo.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gt2lwldpsin.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2drttjycu.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gt2dzmorqqw.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gt2lpkzvkwc.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gplkyqay.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2uznykmck.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gt2rfopxwtn.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2khwvurvn.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gvvpxpdt.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2hwtlppdj.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2wlvkbwfw.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gt2mkzhcyvp.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gt2vyklgmbp.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gt2lewsydqi.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2ejgxetob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gt2jlarflvo.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2owwdjpoe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ybcyfikg.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2vlguyoji.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2poxtjpoe.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2xmggpiuh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2hzznggox.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2risiduch.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2nxvzdqbx.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2wzkumeoj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gt2oofaujpx.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2xjgohttm.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gt2zdfvnduy.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2ljwblqld.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2sziumfhy.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2veqwcptj.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2ichdhmym.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gt2pqdxqmeh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2dbrfcvda.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2wykrwfpk.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gt2imaokqqw.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2awxqcxab.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gt2awvaramg.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gt2cuzofmqk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkftgukh.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2hjwmtxal.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gt2ojhsnkvp.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2nwfirzxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gt2gjeolnxx.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzvabxmh.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2ndnzdvez.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2omntxesw.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvtntxit.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2ubhsakti.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gt2qoiwysdu.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2wfaebwvz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gt2ozctfkla.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyglvrgo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gt2coeepetx.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2iylssgoi.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gt2ahpxkdho.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gt2bzfbuald.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2zhyrqquj.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2iqykhnrr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2cxpfxvne.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2gcgrfmoh.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gt2jmeavhny.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gt2qgfbtutm.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gt2blugcqca.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2hqshprtc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvwpojlh.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gt2dpxvdnbt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2zpmtxvlz.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gt2coogpuud.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gt2vpcjncyg.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gt2lnlujagx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2dyinursp.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gt2xhunvqcc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2tnhwpsyf.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozrbnbcj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2ydlpnfzc.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2tbzmdnow.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gt2qyohqdpg.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gt2vhdlhrjm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2bmiqwkfm.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2uwchozgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2lncxqkib.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2obpgutbq.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gt2kzlonblm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ehfoguri.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2nstdkspg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dglxcxro.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2lnqquqot.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gt2rmmqpsei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzlmstah.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyvpfpea.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gt2aptttzst.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2olynnchc.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2xtdmopxk.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2xvqjbfno.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gt2rvawvsmn.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2haigfkgo.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vpwrgrym.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2tntrerbu.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnqygjng.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2aqsdezkn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2bgwvvdsz.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2zewjsmyb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2vqognhsy.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gt2ydjlrzph.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2sqyjtiti.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2toggnxen.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gt2ozoxmmyz.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biwscntp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2zofmgxsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2ojoisgbj.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2jgbzarxe.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2ajficizn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2jywhchfu.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gt2tpjtlmxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sduoarel.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2xrvcfvrl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2xrtrdhlg.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gt2hfmlbymh.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2xqhuntiz.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gt2odcbjdpb.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmylwdku.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2xdsbehni.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gt2kocconon.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2amtlxlvl.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2hwgfcddp.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2ycsrbext.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2kgjceqsw.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gt2sgzokkum.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2ihjbiknm.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2kexwrgoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2mjizdbum.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2rjlxboki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gt2twixudqg.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2brgmqony.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gt2vgprjkcx.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2ewofrjcp.html


<!-- 参考信息 -->