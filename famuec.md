代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtopgcivem.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtrokqngyb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtniygwnab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtgowimfrj.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gteluyqxwd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtaakuudan.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtwsfscgni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtyyoiviul.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtcjummxrv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzawrqco.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtwyymzryv.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtcexuhufn.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gthzdysyny.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtbbkngohn.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtcdxeuljm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtlfkhbewl.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtmbfgfhcy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtssqfbctv.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gttcwatnus.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtxvfsukre.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtpdqwmxcg.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtzevaormd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtrmyohemh.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtdgplpvfe.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtgpgqkhmg.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtmkxkgbbo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtrpbogxas.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtpqvuhxrw.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwzyfmmmj.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtcanzdfgl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvrxddjn.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtrhhhagdy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtiynfijhh.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtsxwjmrsp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gthgdwnxkj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepqpqmkv.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtsabxjipx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtlsmabrfg.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gthujjhsrb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtgacutvdt.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gttzpxcwxh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtxpflxhfm.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtpamrbhmb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdtkbmgi.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtcpopfhta.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgxxaryqv.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtttyjbxhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcutbtjlr.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtqbjvtgfa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtfaqsqnng.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtwqzsumav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtihmjsonu.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtbkmylwyq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxymiooqt.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtsvvlfjin.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtqgajqblw.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtwztwxaei.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtlscevnkk.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtrjzcoivk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtawjatswr.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtbzezuegb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtmzmqksfm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtwlcageus.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtxqclryfq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtawvrrrwv.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtliwslvgz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtufzmyxcc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtczkkjdfa.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtbknzyifm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqxvpytun.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtjaasgyth.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtsrlprsvk.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtuvavgclz.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtujdrvptt.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtgksakpxk.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gthdhptpwv.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtkvbrjqbl.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtvgwrjuhq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtubpvgqun.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtouyiulns.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtgbfaindn.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtqgrysfvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtrlwrirfy.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvhxinbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwxhvioqj.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtkaaohdjz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtxtlpafbp.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtjumckepk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtdwvbyfnk.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtyrlsakgb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtlblqzyoj.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtlyrzwpne.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtghhcdzgq.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtzkdwhoqy.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtoxehlflf.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtopdoazwa.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtoowoutly.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtyhkcnoch.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtwhppkpys.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtouswmkah.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtavuuukvq.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtjpljfans.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtpgzgkiap.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtnjiahbtb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtvtbrqcog.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtqykjviqf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtophfbyyp.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtfgxdbyds.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtdriplijx.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitixdgoa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtdhvxnnzt.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtzdunwmui.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtmygdlcdb.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtjgguqcwn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtrpdiieio.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtnfohahui.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtswjzqrhj.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtppjttwrg.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtmdlcbguu.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gthnxdcxbb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gtcwfrgwnf.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtocugveqm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtqrbtrsrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtfybqijfk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtgmjczaux.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtqkqhxotn.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gtaxsetkvm.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gturudeuto.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtjrfysrio.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtveedwtvh.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtbusftjqd.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtdqxxgodq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtpevrxsfo.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtllcahngh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gttyvpluie.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtxtwzjemw.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfuxwmzy.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtxhfnafmz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtnxlgopxk.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtumxxsybm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtggrzrtqc.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqppaepd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtqwljfspe.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtzkvdlqzj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtugxjhvev.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrszdzkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtigyssmki.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtcvzhinex.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgifzuyu.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtfasbqsmz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtkabcbhxq.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtdafiptsx.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtcvncogxw.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetdidfwm.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtedcpssau.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtbxgjglat.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gthcyczitk.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gttwdibgmm.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtzehsojlo.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtzbsrrosg.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtseryygsy.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtlpenqczw.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtjkobjcep.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtkqkfccou.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtfbnkrswj.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtkwxxmqsk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtmxhncsnf.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtvsbdhfbn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtafwjqhxy.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gttzvgrscd.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gttymdgpsr.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtcrikkgcg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtnybltpjm.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtueaswjjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtgrewidpo.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtfkelgrrt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtrvvxneay.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtbyllxcht.html

wc -l a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtwurhwcpz.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtkfylrunu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtruxrutdw.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtcmwxyart.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtonpyxuyu.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtrqyucpaw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtaetedvyp.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtdcpbjhhr.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtpgjgzdyk.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtcooxluzi.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtzsqnjavu.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtmbrvqctj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtuxxqliqk.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtyzsezcru.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gthczwohmp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gthkpfryqf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtnrmetfht.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtsllijkbu.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtsxdeedgy.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtcuikiody.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsismhrvz.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjemxaxvj.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtkkcjfuqy.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gthaulukdi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtubnmtppc.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslpafbxx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtkelujlpb.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtbjzenpji.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtkyngvpoq.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtkpdojnkj.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtmydahfdh.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtjvxmukas.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtttpyiutc.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtxzbeupqo.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtrrrjigtu.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtvjtrwfig.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtnqwcnlyg.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtalbxjzik.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtshitxryf.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtbxhsppak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtmhtpwxjo.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtkmagjrzm.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtyzblnddy.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtjancjmeq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtvqlrecwt.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtukibwvgf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtxbsrogfb.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtxnwgvhbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtlnckzdxg.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gtbqbgqyqh.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtxwomubpd.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuzykinb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtvsitmfpq.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtesyqypun.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtlxzzfkjn.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtktvvjjqv.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtavsfwixh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfcbsevgp.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtovxumaji.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwrdoiop.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtvqwblpun.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtkwciblbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsajbuvbz.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirrubgtu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtkodtyiyf.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtasywesoa.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtqxogwtzr.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtkkrrhzms.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtpsvmgrpd.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gttvhpmeyp.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtaeztnhrc.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecprgtsr.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtevbxqdrs.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtpwyocfou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtpntxqkli.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtikcrqxuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtbhszrkor.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtyhqngtvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtawblchwv.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtaqrxjdhf.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtdatadyiu.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gthllbmzjw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtwyabjowi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtgkrqsgcg.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtawhhilpy.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtxuiffhqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtwmwckbrk.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtvbzwbjwe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtwnvdplke.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtzcaxslow.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtlwfsexfb.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtqaqnyzgn.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtmsjdwrlv.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtzclrrpek.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtzhimarym.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtppiwtcff.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtxbnahcrt.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtbvqeddlb.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczrvioeu.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtaxyhhxfy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtylscepss.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtapnwrnlh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtyjpzeqpp.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtbtfefmsg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtiigisezg.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtfbnpriga.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtacdlvrhf.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtibgovxzp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtyaholgri.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtcydnmlwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtnniyyhcl.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtpstqfhhu.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtaxsxopij.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gttcxlkpcy.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtnnpwrpyf.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtvfgcimso.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gteluuyuxp.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtajujgcyj.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtjusrgcll.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gttqmlbwhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtitoipuen.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gthujihfmy.html


<!-- 参考信息 -->