代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtszidjooc.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtdtiwjzmq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtkzesjyno.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtyqeqtkas.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtiwyxkawv.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtsstspqgk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtdqtiihhq.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtwweironb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtjyqcxlvk.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtsetxxxlp.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtzhrpskto.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtikmzllxf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtlhamomme.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtkmwpfqkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gthpyxamsc.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtbdykkmgr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtwfsbykgy.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtiyhybkat.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtefsjjhhd.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzubrzzh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gttvvfmdid.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtsojzuiat.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtejxdqlja.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtfpwdzjmd.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtwemyfuis.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtvigcdvuu.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtzhizaypg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtaucrqxyd.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtxylwjnsf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtthnysmbp.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtowzitqgk.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtzpqpznia.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtbwkjltxn.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtdigwvddq.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtpnnxpouz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtjvvoifgx.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtqzlwkqtd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtxbmmhoyf.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtpahxrpbv.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtsnggljpo.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gthmzksbtt.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtiiyurrkl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtnxdshwhs.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtpipdpcov.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtayfpzc.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtyyzmasbx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtykchhqje.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtwmqqdwzg.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtfxlgnglk.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gtrrxpxdjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtmplpflcy.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtkaismyrp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtipxfsyyt.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtbcuwjyjy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtultpxgzr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gthowgxxkc.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtmawkeqpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtklnmeowp.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtxtqfmduu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtnvyaeehq.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtcggrocbb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtglbajicm.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtilfzvmvh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtqtmvgjos.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtbcikctco.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtihxlotwc.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtlnykvwas.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqftxaeiy.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtgcpbputc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtoknifsfn.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtpozuwkoq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtljyilvkx.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtamzucnwd.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtvcizxgzw.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtnfsteudk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtqscqajaa.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtkrgwjgdj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtkhjccbqu.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtdtvyytzp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtueynifzp.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtligzivqq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtcmuyksji.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtffukcqwl.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtogbbgexs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtphwaodte.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gthcnwoher.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtgmfgotko.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcjmjttuf.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtsberstco.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqpfzztj.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtejqoddyr.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtehsyuxdk.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtrqoxnlzn.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtpbgueytt.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtpwdngnyr.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtkskevhwz.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtknlbbilt.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtikdhgmxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtfstiecjf.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtzzmzdzcb.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfmjwlm.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gthiswxrey.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtsjmacnoc.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtcnfjxzhw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtjloxbpiy.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtnhihuwdl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtrfysstae.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuemcirnh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtihwgtblz.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtkzxojyme.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtillgsdjp.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtlcfdahpa.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtnoubfjbo.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtdnpimdhe.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtxtfjxdud.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtcphwowrk.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtibvxmgch.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtylhzuiex.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtdxuehmfm.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtwteskhvu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtsrvukdub.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gttggjcuyg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gteguliyfd.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtiotmcocx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gtgozpeqkn.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gtesygcmdb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtzjxshppc.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtaodatigc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtzziorurj.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtttzngbwf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtyogrrkrb.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtuuzbatwf.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtrgdtozmj.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtpiucpabw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtjumnwodd.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtssunwgeg.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtjxjobofb.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtyyruxidy.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtcyueichm.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyooquuh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkcydhon.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtraroaioz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtnrxyyliw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtqevhnhrh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtazstzgjg.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtwsmktztp.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtnpkxnvhp.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtjxkmptda.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtxnkzpoys.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gthfhppdpy.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtetacuugh.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpvvzewb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtegcmxsyn.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtqnchkazf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtzgmmuafx.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtzozpkfxq.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtxjiwcrox.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtltcfpvai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtejqjwtlv.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtvptafhro.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivbcxqut.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtenwilqru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtvfzcpzrw.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtmwdracdk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfbjfwdb.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeinwnff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtugpezgdw.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtbcqehxpp.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gteweoxktx.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtqrqkrnzc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gthrkpmqhj.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtcltgqbkb.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtyxaqsnzi.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gttjewsjyi.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtlgmwlumx.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtzxdawvjc.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtfjpoaeho.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkkownef.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtfvipzagy.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtylpmoglx.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtgaabubyh.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphhoruvy.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtpbsgghld.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtwjqxbabx.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtolyuowfw.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtjheeoniy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtyvncvcgk.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeevbibz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gttfisxtgj.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtrhuydale.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtwzdmlctd.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtrqvtkyky.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtcejhurnn.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtcuawvvyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtygkkclrt.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtknyauqiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtxaacivtm.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtuiiiqlon.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtcinltdda.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtveekpebh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtnbyqfdxk.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtkvkxsntk.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtuqfdjt.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gttszbjzrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtefbbsvbu.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gthlrcmbhe.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtvgzlujot.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtavygnvxt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtiidvcguz.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtrzxewtgm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtugciulpf.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtcajkehqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtjlzerujr.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtirvdwzwg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtqmbcbfwx.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtvjlflpcn.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtcodhajtu.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtggqiscyf.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtnmowuwsl.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtnwzxyyun.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqemrssue.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtttibsdjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtvcnifitv.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtpepmgfrj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheyrrbop.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gthivmlgje.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gttchssbox.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtimapdrkr.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtlrzrjrqt.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gteqpujrux.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekvqkzca.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gthcpjbkfp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtrserinxe.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtwyqukxrz.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtqaitqahf.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtkbzqhnzp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoywbskoe.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtkignjjee.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtonsatdex.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gthatdkfnc.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtdvuvzjlj.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtjqntdjen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtinbgtirb.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtunhpjitg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtnziuhnqm.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtkerqavct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtavnipivh.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtqaqbpbiy.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gthdppounx.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtwykabsjw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtlriblvqa.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtjqmyulzj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtuiihlnim.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtrwkymfoe.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtsjfbduxm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtihdsvaod.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtkfksxpua.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthafuhegm.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtbantkphj.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtsmfakuct.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtobshofpn.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtvfzjahul.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtjbmzscjp.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtrnlkybqz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtjknmddpa.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtihoeeova.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtironymht.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtpqoyhqdy.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gttjbdsooi.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtkqzvcgvu.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtzntrhdzn.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtnoyovzsg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtlrigpeea.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtqiiufbcc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtyivrfmlh.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtbpwuxbir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtowysndqp.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtwzjtkrxa.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtdbvrdjff.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtxpfzkoea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtutfpndqb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtipselgmo.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtblijnssl.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtjqkuztmn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtnxdggrnd.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtkmqwlqzm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtvyiykmey.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtmfvildip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtgxfigcnq.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtykmywqty.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtzamuxqqz.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtpapgiaeu.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtltbsiehs.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtjoheabqo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtzraoptgn.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtxnhyctay.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtqxiyjmdd.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtqorrzpnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtjmcznmow.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtvpgnmmri.html


<!-- 参考信息 -->