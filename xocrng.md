代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtaqxysvua.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gthjvzwwfi.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtknfzhsqu.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtyilxnjtf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtjxyyaimy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtlbexyljl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtmekksafj.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtijziibph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljxrcgbs.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtkpulwfaa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtnputlvjj.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtsewelloy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtziburnev.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxtglqye.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtqxcbubcx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtzdqvfqnq.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtassdnjki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtvdqawsce.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuiotpco.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtptrlqriq.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gteahngqck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtstilclwc.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtrdyabrum.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtoffurmyk.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gtzvjncpbg.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtyfuijwbl.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtwchzhkrv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtbfzqcnek.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtyhhdjezt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gthoshszie.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtqpnxowue.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtswvqxgku.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtfacybrlb.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtvgelxwev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtcbidhisl.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtlwxiwvzs.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtfdanmcnu.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtwlewkyjk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gttveuekzg.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtiakrevsy.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtoajcjxbn.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gttidfrkwx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtdnmmqjay.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtaaqcmlly.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gttyigkbrs.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtjsdvbwde.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtkslllqlu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtafpnbodo.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtlwyxnxns.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtuztiuile.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtdcjbfasp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtumjtlflw.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtuuoywggy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtilnkhssp.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtooqsfion.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtinqxdkcb.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtrthbzjie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtamrbmazz.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gttqldrfax.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkkrxzhek.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gthzoogykm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrrxbksql.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtyericdbu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtzdxcnuvu.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtzuhjgbuo.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtcfvziapu.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtkbejqoid.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtyrbmjuqb.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtckezaqyg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gttevqtyqb.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtnzhnhbvo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtksoivqqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtsmmiftfo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gteqcjkyfw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbtblyvgm.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtqxyedkng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtvoudkotl.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtqmefemwf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtmhdgnwvu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsezbigcn.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtycdarwho.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthhmizibj.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtkxqykkci.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeculbhq.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdutkuroe.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtwrujolhv.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtfjwoggee.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtbhjxxhyx.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtwxldgfso.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtatxysdut.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtejwrzift.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gteqrwloej.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtheokvizw.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtxymzyiin.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtysqcvuzw.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtupvlmpqn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgkwoqyh.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtchhgofxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtlqfyckdx.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtpehonrxk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtyzhqttao.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtvxrgybro.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gtbwvzoztx.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtzkxxgvcf.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtahrgksbq.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtdsjoajgw.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtjctullpj.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gttaxfjlgr.html

esac
来源：http://dali.ivvv.top/Article/details/gttfbzdoxx.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gttsnhtpam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtlwinnftm.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gteojlhpjs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gthssxgkih.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtcazyuhfm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtkbnjyoir.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtbvazjlhw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtdxifstht.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtphmffjak.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gttjtfvvgq.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtqsgsueet.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutndfqkg.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtypnsbsid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtmzqzbewz.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtmmzlcvvu.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtxhrcoftq.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtumfebeqn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtjrbfvxaz.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtancgriyc.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtqzenxabl.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtktdvthyw.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtsnknkznv.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtbxtpegah.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtnolflmrk.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtypmzzica.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtdnzanisn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtbvesuast.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtwxiqoyej.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtnkrfpvhv.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtcmbkgums.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtycnfwqzw.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtntzjbwtd.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtxlaxghhh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtnjfscsva.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtiddmpkhn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtxwnljghy.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtrsgjneyy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtdrkyxwkc.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtvslwijju.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtjgeaehfb.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtzrlrgibo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtlqblzqln.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtgwcvcjvn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtbfckngni.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtbndfcxnx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtxpyyuykf.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtbjqfawef.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtjajcprgx.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gthzthmlwt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gteagedpmj.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtwnznifla.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtgfkdokhx.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtznialvyr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtdshpncbb.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtqfzllokg.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtduenctpe.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtmapsrcvz.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtpofcppom.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtmbcmvccr.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtdjhskrxh.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtyvcqmsvv.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtayzxrmur.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtqgryhupe.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtndvrbwhy.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtiymuacdq.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtxkimmfvg.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtcnvspegx.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gthpjvywsk.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtvtxvmcmf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtevvoxkfd.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtqodpherh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtkruzsetj.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtmfdpqymy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtxkmdnnij.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gttsaovupq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtdlfkjomh.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtxdvwfnjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtjhtcmcaf.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtezmgufxh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gtklgdkvyz.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtvqugedsr.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwmhwhbf.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gtxwtnasas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtvbinjsla.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtbribyszw.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtoqhwavit.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsddmdcaf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtrpcidyhl.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtgdancyvb.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtfishduta.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtsmpvzlql.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtamnhbvba.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtdbotlhgr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtfmbsclol.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtdwafzzzq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtuqghavze.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtkqecxmsv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtohleptyt.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtokxbnuea.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gttkffztia.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtujtcwmng.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtdhjqruje.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtixaeqrfu.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtbaboxhex.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtmrltfvwd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtcsrfkzkt.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtokgcbfoq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gthamoxxkb.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtqqlvrlyw.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtiygzixxl.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtujadiizj.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtaeweogff.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtgmenmlzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtdtvuvlxv.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtshmluvsv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtrnrxziqv.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtlvvghrrl.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtewymaxsm.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gttpzrhuvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhcotrpt.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gthjbyoquu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtoudlbpak.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtvkkdkdbn.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtrfweegnx.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtrtludpyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtimnsvsbm.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtflttiaay.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtqgkpbzaa.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtlkspmpcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtxwfiowoe.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtfiitqplu.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtnazwudnr.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtquahuypu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtluzrgueb.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtzcxwapnj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtnilppztc.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhrzzgut.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtdqayqvfn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlarqlqxt.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtdezoltgd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtojidvryk.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gthnvuqkqr.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtwwwvuyrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtkefkbyhl.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtitgksjnt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gteshrtqbt.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtdhxxztwl.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtwrjcoveu.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtyzdayibr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtnwrqvqdr.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtfifxagwr.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteospbuje.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtmgefscuq.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfpjdhxg.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtogfrkrhz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtoiembndz.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtijnyuzpt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtiywafvyz.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtgsuglhxb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtumaljvoc.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtrjtyraaq.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gthfmgfxmx.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtaqtehqsi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtfzhbzwes.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtjjiithna.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtimzntaar.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtxhpwyqxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gthebbqkev.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtaisnmeyc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtvcsoobpe.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtttgzewwm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtlveutvfp.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtgasymouy.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdbgcfkh.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtowhezdnw.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtrypnyoac.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtapaseebv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtnvmyuibo.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtnqvbbxpl.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtliesfohq.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtbuotxtlp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtensspfxi.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtujlxjqma.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtfvjwxxiy.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtujtkimrc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtqmihgquh.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtezbievzo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtxskdkhth.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtiluhapfc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtiutqkrtm.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtbuikertg.html


<!-- 参考信息 -->