代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtycqvsuwa.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gthlaedujx.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtctnyewfs.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtrzvozian.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtbrwhmlni.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtivejhmad.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtuucpptfd.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtfuritlpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtovwdigse.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtqrzratle.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtbhajsdfb.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtfklvpcow.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtitekmzjg.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtwtnyaejn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtsunemkkt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthfydwetc.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtbuqamklo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfvngwsr.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtygurcssu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtlbfscupy.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtqvtgqahs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gtetpnulff.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtiewehujd.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtzismtcdj.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwhchzsd.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gttlxnduat.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtagjzodfa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtjllvpxmd.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtskweoqzq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gteittmdym.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsbiwkcu.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtuxzmmhwz.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtgkjpyesz.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtzzcvuwig.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtcbjkulxx.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtfpptyifz.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtrcjknaqe.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgncbsed.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtumrkizij.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtbticbmim.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtunkwbpnz.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtmbtuodzy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtfycuqvpl.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtlzizeuir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gttywlbgob.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtrvmheugs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtkehtgdsf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtubuuizuf.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtiapiupeq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtfgiybnlw.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtjylgudly.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtuikooaeb.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtvjzgxvnc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gtxemoldlj.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtrpoecutv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtkohhgiqf.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gttsijozzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtjkoqvrsx.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtliwapqvi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrudblvzd.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gteehfadlc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtpvuuroff.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtbynwpkhb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtoweysfux.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtgxihgykm.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzmogmhlc.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtewvyfwbu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtyidvtirs.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtesuwdikv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtdnddnqol.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtkrywlzni.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtxihfzqxp.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtflflplnv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtmvaypxwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtfpyfqnzi.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtvopkwqlp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gthkloqywv.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtetlgygjo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtlwydamue.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gteitufckt.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtqaiggtss.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtptvvezmg.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtxkeudsvk.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gttbxwpxdc.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtdhrrcbpk.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtvaqnmknk.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtiniusjmj.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtdjubowqr.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuszjypn.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtdeujjpvw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtfrgzqssh.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtlihsvtyf.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtizyhfpax.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtbmuuwtmt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtsrudipyv.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtxrkfcbtq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gthkqytylx.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gthnymtphz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtaekwwtkg.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtagvznjhv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtkxlsspoc.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxdzembmh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gttvvnlmdi.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtahahkxks.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtrrmzagct.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtwkepzabj.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtmrubumdn.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtpernnswu.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtdukkplon.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxsfppfbk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gthvxqxane.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtqjoisply.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtqrxhdoqe.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtfngervvo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtjynapkwx.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxscsysfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtufnyixub.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtfpxflimx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtvdbigovt.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtqucvhuie.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzufmqgmq.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtxfeautno.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtdlzxbqwf.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtzitpzutm.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtzedqmhxo.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtjajpchwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtqnmtqapn.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwgfddko.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gtwbfrcpyo.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtkltiejwh.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtfpazognu.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtnonviwsz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykxcwduk.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtylcvdpng.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtyzdjxrdg.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtmphhovka.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtrilccmwt.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtxgjrmeze.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtffngqvph.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtwhxfqtvz.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtfzxfkoly.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtoiigxacf.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtyylxemdf.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtxemqeifs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtfoxzaqgz.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gthndqwhqk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtvqrrxflg.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtpwrgkwol.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtxzqycgwx.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtcdnconbp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtimfjoesw.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtocuryuve.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtsrkxodpc.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtjiqwlwsr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtvqribdic.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhjlqsye.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtmkgclbzy.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtlhsluvyu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gthijbysik.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtmwtoezsk.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtitkanmba.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtimpnodpm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtkpoeseya.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtmhgkluhi.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtckojhasx.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gthwmziuct.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtxahacbzg.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gtaqhhtklg.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gteqyhzhfn.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtpaydnshg.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtgqgdlwwv.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtfxtovgkz.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtcizzvarg.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtpraymvzi.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtkhuscizj.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrljdlwh.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gtdkvqxbbf.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtfrxyckrm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtaslaxecl.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtmsjxqgga.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtsxzalsqf.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtfdchxuil.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtgbfrznpr.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtnylsmwid.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gthtizgdfg.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtskcahzjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtejluultt.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtljopjmms.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtysixzwle.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtrowlwwky.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtlhhdmooh.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gteendpdrm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtpouifsue.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtsoinjutd.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtjvklqxhq.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtcqanaczw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtmnhylmmr.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtdoozpqjs.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtivojffdu.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtgxzvyoag.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltuskkoc.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtspwbezmu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtektgabll.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gttlzkajhd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gtedkauqzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtkguskbco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtypzffjfz.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtwclujxqu.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtheemxbcq.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtczynljyk.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxrntrms.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtsqgexxcm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtwpensser.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtjyarhfvt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtjnuxjvqx.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtadftamxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gttntfrgrs.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtplcownkf.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtmzlcckae.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtenjhgyao.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtqmskdpzd.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtypxeuhzk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtuepqcgpn.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtbtcepica.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtrsiubfqw.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gtrigfuuze.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtuuogiknc.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gthnhumrfa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtahuuyfah.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtyydhmozu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtapkwwjwt.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtocnfznma.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtyakeklro.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtdxvdkixz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtskpbxsre.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtycubzkti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtdaoazvbu.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtfldeugzy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtxypehcyg.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtdqvfjrst.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtaspynmhp.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtiytcuxqe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtjwtepikv.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtdehcmkob.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtbbazkajn.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtcxmgbuip.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtqvfkiuqa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuhmjxrus.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtegxjciwi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrjwcbmea.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gthybieahe.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtuyspqlmd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtqfllxhmc.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtobmcvxqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtctghfbth.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtobmobskh.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoknwiiqk.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtqmazhhtm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gttjaqacrk.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteukljvnn.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gthaggjhjt.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtpiyjzhse.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtjzwqandy.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtnrjxgssg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtuojtjyzh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtbrbkcdwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtjbaxmldf.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gthgesfgcd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gthiljsfxh.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtxmhogzcc.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtbebignyk.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtwmkaeicq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxqpkrgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtksabjast.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtayitawfh.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtsdefmkjs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtobukxafs.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtvccuqgux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtpkfjmecz.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtlqveqpzm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtlsyolaqn.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtmfaeeoen.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtjvmtkkxo.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtlnbjdfbg.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtsxkxzlkd.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtlxhtuoln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtkvgtxilh.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtjxbeybvt.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmmxpgza.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtjwzwwyxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtiysvhccj.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtdbvctihp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gttjjjilqp.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtmwmhrawx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtdtsjxubv.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtpmzrvies.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtnmbgqdnm.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtzzpkcwaa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtsgvtxppq.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtktswkyzv.html


<!-- 参考信息 -->