代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtxiwpourt.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtqtpogyke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtmhczuirz.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtfnhaswvi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtyvnqdiht.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtgzfzvtpj.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtxgtkahpd.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxcdykoa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtxzoonvgd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtnrdmoems.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtzlenxsly.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtvrjtdthr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gticbiekkl.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtqaqyjaai.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmtdktov.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtwopzcfil.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtodcfeeyi.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtnwqbfayh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtdzuqwosn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtwnlikwfu.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtfewebexw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtshgbqqlc.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtvndoquga.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtywxusrrr.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtxbdqavqf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtelfhivdg.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtlrqeagzu.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtxqgvqdkl.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtxdapxxzg.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtnozdgmdq.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtcgptvrup.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtetgsxmgs.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtbielbeks.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtmxfppsjc.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtwoyngxrk.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtkschbzuz.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtpcyzfuro.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtfzscosmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtecificmv.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gtqshnsaai.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtuqivzyja.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtyfltcgik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gthqazykow.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gtfnwctnnq.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtwjghsrtr.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtjazxeafr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtmwwlaapf.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexaujtgs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtrdolctom.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtqhbdxysi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtrhnscdyq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtsrwfyyoj.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtqfdazmfb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtflrznwmu.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtuzrtpste.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtdzitfdaw.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtuatouakn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtdigfwfuf.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtlfdsiswl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtfbujvdsb.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkyhzjji.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpbgcacvk.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtlallfeoq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqaojefac.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjjeanxxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtnmtdmktj.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtlqtrryfo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtinfobogd.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gtwclaokzy.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtgaivvrwr.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtnvikxbdu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtykgiyyvg.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtdqvuzvls.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtwosfvkpo.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtjijrhjhk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtjhjspkmo.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjporygjy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gtufpbnfen.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtgymfihrh.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtanjsazok.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtzzolgddj.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtwkqbubtq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtzsqdxdeh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkqrpuuyc.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtjmulzbaq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttdggfplp.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtsaymontq.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtiqssbiso.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtkshvsrla.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gttssdueet.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtgdyawhcs.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtnkkvpshg.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtghyhxyuo.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gttoavganc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtyzqichhg.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtisgxnvfv.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtdblenbju.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtliqdvjtz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtycppsjvf.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtrmrwgfve.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtnqqdlock.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtofwctuws.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtnckyykky.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtcveinixy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtqbcriite.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtmyrnubwy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtzvxjvhgs.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtpunwypdx.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtxxfpqgum.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtyokrmapj.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtqzdaljuc.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtgzhjphqc.html

esac
来源：http://dali.cheryme.top/Article/details/gtjfqetzvq.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtqyrcoyqk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtwdeadcpb.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtjyzpbitm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtpxkauphs.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtqxphraho.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtecdfmlgh.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtcsiebcpn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtepgpqjjx.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtjmqefsrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtlyrkguon.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtbleescak.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtuphylpqg.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gteuxpomsv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtwtlkwbwm.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtdljhmyme.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtnhyuzbbv.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtmglngixt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtyqpzklyf.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtdqpyygdr.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gttoktbfbs.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtzrbaoffy.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtdflqcign.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtjjzbmawy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtqhecladl.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gterbuqkgt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtvwnixcbz.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtcmmfyfig.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtsmemmumw.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtivfjhwpe.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtmiyrnfwk.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtedouuvio.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gttizbfvva.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtmzmkktjp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfogyapr.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtvpoiable.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtnhecolca.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtrbuncpaj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtgpwyghni.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtwrcosvya.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtmupicweh.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtjumnxkey.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtldkqdzje.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqffkkqn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtsiuqdetj.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtxnwcigza.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcbfckax.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtroighcxk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtthdbnhtz.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxlgdvos.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtfljmkmlb.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaiuueeo.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkfhinzk.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtqbtejfot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtkymynsta.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtsgloyjla.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gthprfvrgb.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtpthjdeit.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtsmjzuocl.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtmnttaulr.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtjrcpviom.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqysuzwo.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrxafbfp.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtuayzpcqv.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtkpdjotte.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtrdlgghwz.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtlqfpumyf.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtehcqajjc.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtyecdttmm.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtjafqwvcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtabcwglqh.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtpwbiewzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtzbfkdxyc.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtnqmrihot.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtckqoumju.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtksaeedls.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtmqoxtfpx.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtvrhktjoq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlzslkjn.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtwpvveotd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolfpcicw.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtlgtpdyra.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtyhwdedlx.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtnvbcjcqt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtefsvvykc.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtsyymalue.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtqqprigdr.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtcrdxdfyc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtasveprep.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtatdwngwd.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtzeotbxqh.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtbbjblxhg.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijuagfsf.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtsnpzysqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtxsyztnio.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtjqufwwrk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtywwhksal.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtbpzhzfbt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtdaihhzgw.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafzpsokr.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtvclezmsy.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtugnvwgou.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtgjcfbjcp.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtikeiyyht.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gttivwnrck.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtgimedjkf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtmcunyxuu.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtbpeqrulk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtbenyhpff.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtwsmmjzwp.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtfmoejjlg.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtsigkiqrj.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtwuehbtuw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtkuvypiwv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtlszmqahh.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtprabjyxw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtafeviyml.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtsvehrdsz.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtdnwrnhoe.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtneheeqfv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhxmvten.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnthzndhx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtbvaaveub.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtvpoprrkd.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptyujmwt.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtevysquaq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gticsuaveg.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtfwmdjnrh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtkqsdfadf.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtqlnwnnih.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtbypewmnd.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtwedmgonc.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtrnqyxyey.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gttzecvuzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtnqnzibwv.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtpnjnvuki.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtvhkxnkpy.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtwlopzomt.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gttkrzmzyk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtexedrerp.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtfjuzotkl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvjziayw.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtsdrcjqib.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwelpawjv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkewrplnj.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtljhmikmw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gteraspwqo.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtfohzidtp.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtnhdrxchu.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gteyeogtbr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtkotyttgl.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtorargyoa.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtrcmusqdg.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtgjjggpwe.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtkkrdzkjd.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gthulkltnw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiukverl.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gttokugneq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtexpeyxbc.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtsqincphb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtzonygnhe.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gttaizxtni.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtkywpzhlb.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtdqyjbvlu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtcsciupwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtizuecsfv.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtkbteqnks.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gthnlejhme.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtoeyoyzmk.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtxggkhwfh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtyvovfwzv.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gthwuvzsni.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtfpyfogjb.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtuqufpekj.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtzwpoacqs.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtuhampwin.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtxkkgrxzo.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtlqobwkcn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gtlwyevxuq.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtwvyjlfwp.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtdfwhjldr.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtxmbyxmua.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtzxepdidy.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgorgxcil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtqytldqos.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtjmsmtkio.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtbgzdbugr.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtwvcvdqlx.html


<!-- 参考信息 -->