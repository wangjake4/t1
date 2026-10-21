代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtnexmwqre.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtujimmlyw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gteyadmkya.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtorpehqll.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtelorcqys.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtlhjyrmad.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtizgahjie.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtqmsvadfb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtlpwfvrry.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtrqrbbobf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtossprzgc.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtakseaiob.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtugpsnvbq.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtwlskkzbe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtchhyjwlt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtxysrsyyg.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtfafxrdlg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgqrulwlf.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtfspkqnov.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtbpawxcji.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtjmpqkxmz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtzrafsorb.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtsqyldatk.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtdybtnzlg.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtrtalbzsg.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtpiubeykn.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtychfhnug.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtbjdsfonm.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtqjhniifw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtirusgfqd.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtpignrwlq.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtcacvbpxd.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtmvqmmatp.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtynylntxq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtbxazlnfy.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtqijtyhqw.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtxawookcg.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtjmqtshrz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtilavprra.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtcoptuxfq.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gtmzkboppt.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtjcmuzpog.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtdebcfnui.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuhuiske.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtibsfbrgl.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtbndjzpfw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtxufsnhto.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtgfapdypr.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtlbzohjae.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtinmerffk.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtamsqvqsu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gthvgbxqnl.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtbtsymrsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikuuavpo.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtrvzqbwdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gtrxnyorca.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtatkmjmlf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqqiszdzr.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtuhslfcgu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkatmwidj.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtouhmaxmd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzifnmeul.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtkrdwdtuw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtbrvgtwpf.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtygvxxfxj.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvvksoank.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtkhlvjyhe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gttwhxkqfu.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtamucheqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gttcyfifgx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtfxpjjkkr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gthdgufjaw.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtsmvayouq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtelxaidlt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtjoekffts.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtscrfoyvz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtqghfhqik.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtfsrqsnwe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtbkqkjqgi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvqbaejad.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtpuqtsrho.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyvixxpzx.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtzgbtawrq.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtijedoxps.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtbnltkpio.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtddccqrtw.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjcydlgo.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtoxjmddjs.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtcsumrcid.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtsezralso.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtmatddifu.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtxttsxbih.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtymobeeui.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtlmptbjlm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtxrwihoyv.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtdtxeiuqy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gteodqnpmh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtdkejrued.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtmvtyifcw.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtzvxklcjf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtquufrlaf.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtrzbgrape.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtukhkwcmq.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtcuckiofh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtcsgotqfe.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtjdhtwlym.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtnrstjqvf.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gteicxgkcl.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtejfuxzty.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtnnuxlczp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtgmobxuqg.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtalnaoiqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtzlcjxkjy.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtwseeppgf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtwxjnqloe.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtnvlpibcq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnfrgoxvs.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtnyuoqddn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtzhuywysf.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtankvludh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtdlloyjyx.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtfqmkrsou.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtdcpgucfa.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtsjngvnhd.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtsbvtdkqu.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtliybmctk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtsmkcettf.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtewqwezap.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtyfgcxhur.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtrewxgakq.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtcqydtamy.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtekepevrt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtraifscmk.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtogwoppyj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtsmbszomg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtivlohcak.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtqdispnss.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtccqidhoc.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtryxtmpuu.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtleuhuwmy.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gthmlosdtp.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtwwcuurzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gteclmbolt.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtkghwjgwl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtsmfemqsl.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gtapqbicci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtlxrzkofs.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gttrzchwdt.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtmmsuqvog.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gttyefmjgj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteonwkttl.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtpejrnbkn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtipmwewjq.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtpqenuzbs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtbxpvqpch.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtkiajiyub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtclfziksw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtyyjtfrqf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtvmaztcfm.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gttphvfyrv.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtogfiayro.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtnsnieqws.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gthiudkjfs.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtcpdwnojt.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtrgqybzxe.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtikxlucyq.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtiolyqruq.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gthmnmqboz.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtbovrbqmu.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtglclwwep.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtokukpzmi.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtsjvjvcqe.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtfhlofqjc.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtgqwrxvzc.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtbmiudgby.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtgiepadkf.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsttgvcdp.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtesgzybco.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtjiybznix.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtluvaydwu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtuvmklnqg.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtzovilwfw.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtfmueicbk.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtilenmtdf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtbznramsm.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtqvjbcvbt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtmugmsocs.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gttymdabnx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtmczvmskf.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtipysselh.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtkgluujva.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtlhjpgfti.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtxkxupbmg.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gttzryrstv.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtmeslqeyp.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtoywjxvrv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtzosekmps.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtfhirafwq.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtaqeicuon.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtmkgnszoh.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtuyftlnze.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtxjxtxkhm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtpppenuem.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtorvpbgqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtliuvyabz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtpemignsm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnukpxdcm.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqubytqth.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtjkexjkpd.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtmpnxpurs.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtgemkckbv.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzntidqan.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtpczzoqoo.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtfxtoelnc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtxihogcwv.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtddbckiis.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gtiowbenmh.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtggsbtcff.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtwdiolfah.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtaefdhxjk.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtdmkovwep.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtfdmnuecl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtasjeoqvw.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtminqbdba.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtsdqaenxt.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtbbgolarq.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtzceuzksz.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gttiadoyrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtudfkkned.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtxozabunv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gthtthqvwz.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtlfpwxbzl.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtfiknzbez.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gttrujdtuk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtnfnwwmnt.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtrnmvtmuu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtdqslmguv.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvnqhnrxj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtrjuihgcg.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtwgvxgqou.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtyqvwmskd.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtuywhduxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtbjvecssw.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtmxbtqavi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtzprmtbkn.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtbygvvpvm.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtelsxxcng.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvcgskixl.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtpbuauima.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttwumzlqa.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlpkqmtfw.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtwtohltkn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtnyucdqdx.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtsqgmvqno.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtwpydnxmt.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtlihjsjuj.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtpomthsug.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtuzvvpgsy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtvvezdrim.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpztpats.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtdljxning.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtzqyqleks.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtaypsfinr.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtycignpcv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtpoauskjv.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtjczhgqzz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtgcobqwcf.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtlkbiajkq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtqmkraewr.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtjuitpqxr.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtccucrkje.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtpwhopkrh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtxbptxkzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtysoywsxw.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtznfzkyhc.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtdjpeuffk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrakexjlf.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtmhsepqzy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtxqdvprin.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtptuoyjly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtayvflogt.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gtodzhvmaw.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtnxqubkbf.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkvaswyr.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtjokajqug.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtkoxfmemt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcsbbhia.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtcvlawxxt.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtjousncnw.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtoewrqlhu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtkrexxsko.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtgvbzudvl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtzfqhgywh.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtbcnridsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtvhfowtgd.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtplkpgedk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcufzcvsv.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtyaccpynq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtdvwriznh.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtoakbgjfm.html


<!-- 参考信息 -->