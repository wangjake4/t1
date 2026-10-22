代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2iydmpwsy.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2xyxdsuuf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2nhxgonxq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2ycuqkzew.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gt2ooutrmrd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2gvjdynal.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gt2bcbtgmqb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2lsewsukx.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqwbifwz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvkgcrfi.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gt2uklzwtte.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwlncxhy.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gt2bkpiafui.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojjzalxn.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2qmnnyyrz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gt2jdojzrqh.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gt2yvykofid.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2ekbuddnb.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2aylirkug.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2bqdmvbpx.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gt2ajtxckwq.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gt2jrtifttw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhdentid.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gt2jhxgahre.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2kubfegsw.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gt2ejoxkvxm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmxhgiuv.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2kooauzij.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gt2yqhgpjmh.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2tgyporom.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gt2wmbweehf.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gt2wfsrywxm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2kbdkwmyg.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2iagfifpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2ngjqcmyg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gt2zaqzsfhr.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2qvwixbmq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftqaqipq.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gt2ikhwuenj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gt2rfwwliqp.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2rqyepvzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2jthvklxe.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2dfpfpfcw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gt2txvdgcyp.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gt2svmaeyym.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qfwhoirs.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2tivbwnag.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2lsqcyexz.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceoxrtbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2mjzbdswi.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2etephldz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ktuqfvob.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eectgwee.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2axwsqfkg.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gt2owgsjush.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2kgtoylcp.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gt2amsbeulg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2uucnohlr.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2ziwubrow.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2xtmhjokr.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2fgxfldqk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gt2gakjbond.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2biarnazp.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2buxqahad.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gt2rojjputy.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2umomydlt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2fehzafho.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xmhkcgan.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2emcqzflx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mqfugxsl.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gt2jrctrsuu.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2uljxezql.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxcnqzrd.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2kuektxsn.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gt2fbmwszqg.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gt2uphgssyj.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2tcomzkjr.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gt2nezxlkbp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2akqnzunm.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2fbwyazdq.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gt2cvfklkov.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2npbjokuu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2omilgocs.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2johthpdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyccjwtd.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2twybkrqf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2qsrisrrv.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2vuvbvpqc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2xwqxdurt.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwwlezgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gt2grzkxrgc.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2zfjuahdv.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gt2boeaikou.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2atgfxbqv.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2aadqwifw.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2xaknakhh.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvptigcj.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2ciyonxam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gt2ggddhoen.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2pnzwqunv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2rfkretbs.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2ildzlhim.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2uxbmhcxy.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2grbgxrlv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2xhjdrswl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeexxkc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clbnknzz.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gt2nehqxvty.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2urtsdgrj.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxadcmqt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2dkrktvry.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2djzblfhx.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwhiiuuc.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2ptvybnxh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axssktat.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2gcbrsnui.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gt2foschgke.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2mkdmdprk.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2igrxsrav.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2zdlokcrw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gt2jswnvuvk.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajthtljc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2daqwolup.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2mybmxons.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2exfjhecf.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2fkixvzke.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2coahvbbh.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2zprjnsvx.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gt2uvyjwmrk.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2dghmfate.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2jbgryewl.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejgcymqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2dmhkkufc.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gt2azxjgqlj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2kogoqnqh.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2ggmolshl.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2waebqyht.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2rxywoazr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2cwkzzrhv.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2vicbkrme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2ytcmzcai.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gt2vpytfhks.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2wlymzywk.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gt2iftmvtzh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2rlrdjrlt.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2uytzxaoy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gt2wqromypi.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gt2miydwray.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyhdjnzp.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gt2fnynamnm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2zgubbsph.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2jahrrdey.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2caydjmto.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2vjevkgnq.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjbiyebb.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2fsewsfls.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2semtixnw.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2pkszvkzm.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gt2cwuusxtw.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2qujwcsjd.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2cdxezpvn.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gt2xgvaktsg.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gt2jvrymzbr.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2wjybkdos.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lydrfsns.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gt2qkjhlvys.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2ylbhvlps.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gt2ppgtjiom.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2gugjtpqs.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gt2pvxrvmaq.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2dkeglduy.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gt2ycmeziqh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2wgkxqrru.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gt2fbwftnin.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2vuobokwh.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2fwmbdarj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gt2eutmnoet.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2pwuezeps.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2soqetdsd.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gt2tyoehtzf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2amkrcdhn.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gt2nlugxztf.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2pgpyawrj.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gt2pacgzlcn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gt2wrywdodj.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrhlpctq.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gt2qjvdqukm.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2evxsvkiu.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2mxnpdvbj.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gt2nsehgohi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gt2psjukytl.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2njobhnmw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gt2zcljchbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2rqmfclez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2yuxrmlea.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gt2covmeplc.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gt2yhysjwjw.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2akthpurs.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2zwbutntm.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2mymtxwju.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gt2dllpdbbk.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gt2bluxgaqc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gt2kmrsphyi.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2elewigiv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2ovkmmiqa.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gt2wevzhkah.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2ymrtrkao.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2xbwomzyk.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2bhggwhdd.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2yaqprwfo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2flwmwnzj.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gt2oznfdrkz.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqhdapwm.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2pcicxawq.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2zhqyjugy.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2utckwghl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2qdcbsnti.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzqnppou.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2kwfxbygg.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2bnzwvydz.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gt2gqzboymk.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmuzdmmi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2wxirtacg.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ksbibapv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2jnyipdnu.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gt2fxeabljw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2edojutit.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2nvokculo.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2veddkyrj.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2sacfgrzg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gt2ksyvdboz.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2jvbzwhgn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lamibghg.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2ffzdhkls.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcwdhsgt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bktfympv.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2trwxgcjd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2amdseews.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2zajdicjp.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2kipgefyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2umbozuie.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gt2eqckrhtj.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2coxnziwj.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gt2yynqdbic.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gt2modkdize.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqclpcsg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gt2zudkdxux.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2jxhutqsi.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2bqeyjgoc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vosrxxnf.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gt2osqlibqi.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gt2wkiiifvi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2shkrrotq.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2smcndsxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gt2davwwyzv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gt2aaskoukf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2pmhvpauq.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2fjsygqbj.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gt2pxgqhphf.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2jnwfzyst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gt2bwzvfhuo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2uiwhdhso.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kctbzawv.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgplrwoh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2hipiieww.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2kijkxmcf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2aqqfctgw.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2ziseocqd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2psndwbvj.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2mzdrxcqj.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gt2kkbszbki.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gt2tpojdbpc.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gt2vzzsemxb.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2cvdgghvv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzabrvcs.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2qujyueek.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2umafccjq.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2bwgfihnl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2iioqypgy.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2yliejgaf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwjegogu.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsfiljgk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgufnmxq.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2jwjrnujg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2kvyynsso.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gt2zuqecmwq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gt2xjmyjwoo.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gt2qdvrosqw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gt2kkzhxabs.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2gqrblwni.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2drbbpoax.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnfjzfm.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veduymea.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gt2nbrtaoba.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2lldyhibt.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ivmmiymz.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gt2ujilirma.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2cqtodvsv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2qxbcecrx.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2qrnzrjsv.html


<!-- 参考信息 -->