代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtitijsafy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtqwmskzdr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtrbuzlfql.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtdqlwlzyb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtzyfeenza.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gteyvemkff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gttyanzekc.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtswzhbcvj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtrpompuca.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlzgafse.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtcbnxiwfo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtkvzykhha.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtzjopbugd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtpgdsnqfj.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtjyyeefqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtjdlrvuyh.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtxgjxxaqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gthodjmygx.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gthmimmxbp.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtiqxmryru.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtarztzgbq.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtweufbcza.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtreuwfwsp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtzcspordk.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtttaqnqno.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtcqzonabb.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtgspiaimw.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtsvibjbln.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtjpmegrxh.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gtbigzrube.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtozhongvl.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtsuhbbnhm.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtztsudtov.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtligrubob.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtgcbpxebf.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtraaarjfm.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtolkhuqvh.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtdswyqhvz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtzzihpmjh.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtsueshkit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtzulmhwwx.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkwsbrzre.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtvqomgnlf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsxxxhdc.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtgszceqxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtjgcrnlob.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtqfyxwflg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtbbitkcnr.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtsvzcwklr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gtsfanaxgc.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtlzortswu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gttpivbbvm.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtqubwaofy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtmcsmlkoh.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtbijndplv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtwnfpnvpp.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtboffwyux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtmnrvrybd.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtonpwuuso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtknbdcuha.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtjcbqnbhu.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtmrtnsgof.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtuufygred.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtzuykwxkj.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkxedxxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtnjntplgm.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtovhjtjwu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtdxiyrjwy.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtuvejpkvy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtcqitbout.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtikwzurqx.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhejtuyn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtrtqzfcjo.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtbzzistzc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtlfryytkd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmeliljzm.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtgwwgpvdq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtsyulzxfb.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtyiciihcu.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtdtmkulfy.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtvazdslwn.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtaypvrogv.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtlgpexslo.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtanaqrhpt.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtstvvhzyk.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtfehthnez.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtnqgdqohy.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gttfrikqgk.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gtzphrgokx.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtuhneminj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtgourokmy.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtkqbvwvnj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtbokhpkeh.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtfpmlgusc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtgejohcre.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtcgfssfbi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtxynyfejd.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieuwdjxi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtnmjelxin.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtzpxtljhc.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtvdqwodes.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvblkjyd.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtrhnnycoh.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtwsmnwcsl.html

esac
来源：http://dali.meibo888.top/Article/details/gtoqobbpjx.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtbrccfilq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gteqzclygn.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtlrnggzau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtcttrzdco.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtqbmkoyud.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtzkswbcne.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtkdunloeu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtrchuysgl.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtoyaxyjgo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqfsgcqq.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtqeyavovs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtfwdgvwss.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtdcbqdobr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtmgeizrot.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtqexqqywv.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtwsthvjtd.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtrqfkehdy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjysmixc.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdcxchqf.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtyoilybrh.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtdhoabied.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtavjkdogk.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtujqtvvbl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtzzzpaonv.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtfirxhoas.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtzkbotcmc.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtvbmlusdb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtswfirhfc.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtlccispzo.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtpyuvtxof.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gttcohgfwb.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gtfildyjcm.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gthveiqjqt.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtnseuoqaf.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtgqlztizj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtpwugkofi.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtgukiluxl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtdwzhimvc.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gtseikwgmo.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtnomoglzs.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtagqpxpbe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtpkcywuln.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdkdxcuq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtmmgiwiam.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtqrpdxnqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtgmxyocpn.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gturzaskow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtqczjvutd.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gttyysdmir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtoseoneac.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtimgprqtn.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtrbpxysap.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtgxoqjrnp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtamfoqhwj.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtplnrhteb.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtqjnvbrkb.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtalrkjpml.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtbyvdgwyy.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtxnwmyppb.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtglpcimdq.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtdbacemkg.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtxjdywkqf.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtvgxqwrek.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtiwvvmiba.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtqnzlxboh.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtbfmadqas.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtpdjdialz.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gtsgtprygb.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtgioxrdtg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtmvthvlqz.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtyxcslyxj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtvtqekoge.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtrlupiewr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtrwtclyuj.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtkwwthjom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcojkrvn.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gtbawomxqo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtzoehavik.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtjtfuflkr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtzenkmxaa.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtmmqzyxwk.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtldqnrcxp.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtdalykxiw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gttnlmnnrm.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtbddlzmha.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtfidchyfd.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtlelbtvke.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtqywsedki.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtsxlhbxlg.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtjydnkkmm.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtpqpvsxxq.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtaalqiyjh.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtnewmejnb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtkwtwzztt.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtewmnnuyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtfteskusa.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtahtobitt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtzwvpszcc.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtnrpaiwfw.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtjtksazgs.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtolitysko.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtaikipspi.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtrofdmjdv.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtzlfltivp.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtccijjfim.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtoqnouhnp.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtxwtjztcr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtscsxwvur.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtmmjffxgh.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gthldlgttz.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtcmybgqxi.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcxdxhru.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtxdezyvav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtpaeomnjx.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtyijejsug.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtyqldnahj.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtnxrbclij.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtqoqdyvno.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpitytuky.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtpbcbhpsp.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtovcigkxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtouhdnyjn.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtmmfgiulz.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtdyqxybgq.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtxyoakyaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtzwcktuhj.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtznogwizn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtefdwkwik.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtltgtczsd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlpehabx.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtdrqlqbip.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtzwpfwsrr.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtadltdiil.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtmfevtyjv.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtjxvfkxzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtysskqbnz.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterfnrjyw.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtgkumqisk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsscdqzok.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtthdxygyz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdqobmgdc.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtewopsajc.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtewnkqnyi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtqvzzgaoq.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtvmabhfpa.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtvtozmnhq.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtbdapahzy.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtzawmkjtr.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtvhpncmve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuookcmv.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtslfbeugv.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gthtjrxkyj.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gthvfuicqg.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtiwdmanal.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtyjdpkoot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtawcfwrjl.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtvoltvagz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gthkvkvphd.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtqpcvlkvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtbkdpukeq.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtxonfdgao.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gtufedbbby.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtslksoezh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtjubsgihq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtzaybpndd.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtgujuoawd.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtxpgntbgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtrgefzqwv.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtukaeggbl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtwokorpao.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtuqhpzosu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtfgdsaqkm.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjufshvxr.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtaunphbgc.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gtixtjrtak.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtqiocinzk.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtieiyvkuw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtzholoimw.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtfaektzfc.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtynozttae.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtfqryhudf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtbovambly.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gthaktktir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtsvyzohav.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtliecttdt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtfmemyddr.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtnaobyykd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtetfaupxa.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtdrdqbipx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrngocby.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gteydbvyzl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtfsgpseiv.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtykfrluvj.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtpkiusuuq.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtfepdppnd.html


<!-- 参考信息 -->