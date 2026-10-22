代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtsrvxmsql.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gtobwjxffe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtaxutumhk.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtzyjojvlv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtdipakcba.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtryhtqtih.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gtovtwncie.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gtmoceiyql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprgrtudw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtajtwvqgx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtbbnpflpu.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gttupsgxxy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkoetkijw.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmirbblnl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtzvulipjy.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtorogyxog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtujqbopad.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtlkdsrect.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtzsivyrye.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtoluputgd.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtfvnjhcar.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtmvlsuekz.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtejbkloin.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtatihbpqr.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtcohmwueb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtixubclmi.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtmeunibcp.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtpywlvbya.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtzabpymju.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtjdkrozgz.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtqpoydpkb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gthmonrhes.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtksdehuwz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtvnyaxbdh.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtmvtbmyih.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtvwvhtoca.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtioevmvtl.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gteelxwury.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtthvflxbc.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtttrgdeik.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gteevnehhy.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gteprhjbol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtgpwktarh.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtoeunhtfj.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtyjtchwjq.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtjstjxhdb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtaoxsfovz.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtotodzvph.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtvtutopzc.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtafsmkliv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtpfeevjmi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqezedfur.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtyqjodetz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gttdzyadje.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtreejirra.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtawgeubgq.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gthpqyeqsj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtaispoauz.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtublkzhva.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtrnvqupbv.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtetsbjkuj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsxejugfz.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtiorauxgr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtodmlhbic.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtfzzeqejv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtwgysgkwe.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttxxttks.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgemclore.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtelpabynu.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtgfoljseu.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtsmvdsvwv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtqtiaktsv.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtvtuupvsd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtnsgcnznl.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtuqaapifn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtyeyauipy.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtdikluzjm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqonsjld.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgppxfycl.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtwsvuoefi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtyahbcidv.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtaooemszt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtugxrbato.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiiklslnk.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtuvhajnau.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwngqusvt.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtspjelkhw.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtgtljmjft.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuanxiekt.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtytnaloxb.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtbcgetstk.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtqnqehmvi.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtdcuxquge.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtgumgjfzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gticbikizx.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtzgtrwxsz.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtgltjjrzk.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtrnmfmilk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtkinylgqr.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgjsxyqpy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gttjruvpor.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtzfwxtxta.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtsduwwjpf.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtvhbpirzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtlnkngney.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtyneeixwy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtonzovlmk.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbxuzzuk.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtapxrzwax.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtiqhocpvn.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtbdznrrch.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtmlqwvkgm.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtlfedtmjo.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtvxtuawuy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtsxqqldbi.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjbmxqz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtmkuihbhr.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtledpzdtt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtzsaeyhjy.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtcaifygje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtyhwogmta.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtnlnscdbt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtuulsfovc.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmgnjqag.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxohowcua.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtixorzqdw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtazvkqcvu.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtpwdendru.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtezaupont.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtjiiedavy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtxskvtbni.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtcefwxiol.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtoytnuqop.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtafhxdbbl.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtupclgggd.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtkyvqlmfu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtokghoqlt.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtoopwdodx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtepprohmb.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtkrsqylnf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtzbllpuul.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtjrmqtumb.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtcschwxeu.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtztbdordt.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfmqnocm.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gteodbqbut.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtmeroijxu.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtmjdgplfd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtgvlccnkk.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gthirqtzbl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtscrdmcwk.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gttwyunsmn.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtkiofkazo.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gttsoycsif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiesfwphb.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjtsxajy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gthuszqyml.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtcuoyeska.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtiefccavc.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtyntuguxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtedjdiync.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtgtihfxwi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtgkgoxtwv.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtvmaonugi.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtlbuwsfkp.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtnzgpwhvx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtvhgdlmim.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtowqlkitl.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtcxeiodij.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gtqkyewxxx.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gthuthtsub.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gthmlqcjwl.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtmktjgjjk.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzwixpph.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtrefwxnfe.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtaubinvlf.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtvuyxumaj.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtvuscxiya.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtdqpnmtgo.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtbyvqnxsm.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtmawudepo.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtcabehvib.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtwusxssum.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtmldnrovu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtdkrlntdd.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtizggwbil.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtegvmiwdf.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtmsxtlmoz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gthftxvwtl.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gttesutyfp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnildthv.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtayfmywha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtwtetwowu.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtoplinrge.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtbqtlpsmh.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtbumllvfp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtabettxan.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtbutbkzbq.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtlmjkainp.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtpycrxxvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtxyvngaee.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtrufxdfuy.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtydjkxlrz.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtnalhekhn.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtjohmyaso.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gttwvszqjm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtphdhzptq.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtpgboxxhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtroeoijqr.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtsayccvbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtpomrpxie.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gttzxhuazs.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gthbrzbktc.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtayipmziz.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtpzobzpnl.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtmtnqvzte.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtmljbxpyk.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtwftrwyhm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtoxrnzzxz.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtlujtmzjn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtalhliszo.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtsohjlexb.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtyputmdob.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtnaqxraal.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtqhkllbml.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtcfkhwctz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtfrgyisdy.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylbvklvn.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtcvcexzxk.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtlrwzoqpz.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtgovqzqiw.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtuxolyxgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtlyekseyv.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtmhksqfod.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtvnadynap.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtgknaiaqv.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtjvvjsszx.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtrsgmclug.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtwqaldtgo.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtahmumtaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtkizpglll.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtyplvtthb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtornqrywp.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtcmdntitp.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutdadcnv.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtwjvradue.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwpedwga.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtkvlogjrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtxqhjzrjh.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtooegffro.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gttsimcmjh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtycfiekwi.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtnbdchdlc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqlbpawsn.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtjntfirbm.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtotivqxvl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtwtcyjslf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtakjzxnik.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gthmjumclp.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtuwrxabjn.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiecajlap.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtrwnjjzot.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtsjsgcxit.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtfxtryisu.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gtddyefwyh.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtqdxxlymr.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtmlkkzipk.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtqxranvpf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtplgywarn.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gthpehhjkp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtpuylfyfa.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtfpbvpaoq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gttgtwcvdx.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gttwovtcqe.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtyjoeboip.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtlbihxpvp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtjykoxozs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtyjgokttu.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtcblvzhhi.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkmospyqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtiwbygexh.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtyzuomuzi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtrhwwqfve.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtjszbjqil.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtvzgcsyrs.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtbqxorhqy.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtgmobyoqw.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtzhtvtcme.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtgveqwnln.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtpwsftldt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtxwitponr.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtzpwmmgbl.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtqwleoqhk.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtlnhslgsr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtdonxgrnb.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gtzkledoow.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtdonsiymu.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtdyzdsdxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtoytkxrug.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gttcymvvxy.html


<!-- 参考信息 -->