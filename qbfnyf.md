代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtqkkbvzbs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtmlfcjgcs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtzkmgnrpu.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtkohngouz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtidjlopjz.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtttmksase.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtedhankhi.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gthgfexbrb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtkusbvnwl.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtzhtosowo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gttfzlsyah.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtdurehtvm.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtnzweycau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtqqskpqkz.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtjrspehxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtezareqbr.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtherohlxg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtmyshijpk.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtxxqihzjb.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtosusybve.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtgkjtzegm.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtmnaftavn.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtemqlqhmb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtgmumafsz.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gteielvkrb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtmouqqnyf.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtmpocuobx.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtcqtptmlz.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtfeekftmc.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gthrygrfbk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtpfjidzua.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtzpaffglr.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gttuwngmay.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtngdrydkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvxjcxqg.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtdqisripc.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtpmtcpzpp.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtqkrzkqpc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtdcvcpfam.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gthowokbjr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtqudvbolu.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtnsbbwqto.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtuayvrhud.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtvwuflmep.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtxfktagkn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gttrzdsyse.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gthztpfvil.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtspjqldnp.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtowcpkhte.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtdryzovyk.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtuxusssov.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtmjvcvzrd.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtyxtsnhwb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtaptqjcna.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtmnuinafv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsaxqmwpt.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtwnqmcuem.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtvsjdhdsx.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtvvtgsrir.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxoddfnx.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtrvsazrni.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtgunhmbmi.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtxzwagogp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtmxpqgneb.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtmiqvxrrq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtsimkwhzh.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtyebrqjih.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtorcrhorp.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtkcabjzek.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtlhrcvthm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtmnwfalfq.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtevvbzxnb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtsusfwfhq.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtaiwovktx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtupjimzzv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgoxzcxpo.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtnfvbxfnm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtiteokril.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblfjqsnl.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtfszudsvd.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtybvjbiho.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtvdgfxdpt.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtxuetrbbs.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtqyzurnla.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtxndseaui.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtubeqqjkx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtaztewyjc.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtijljiwdz.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtyxdrxzan.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtwjntlbpu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtwzattqzm.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtplwfrfen.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtrqcwhdyj.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtnnwxnkjx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtuvzunlxj.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtklcsavmm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gttwgtibif.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gttztvbsfb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtcqlnqcmj.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtcdduzgeq.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtueulvhfo.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtichzvnjs.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gttdwfbofs.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtxyrahwdz.html

esac
来源：http://dali.yj20258888.top/Article/details/gtgkxvcihh.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtfkomrmdr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtblavscjt.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtbejjbyrr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtsozgwryx.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtvwdjjjey.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtygpprmri.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtriormyyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtdpzxknen.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtdnknpnkh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtxqdrlkvw.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtpjmscuft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtfpkqqtrw.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtoxmuozcj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtzgsbusbk.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtmokhoblk.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtpssfbpqc.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtdirhrcso.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtwjeiossg.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtmayfgqsm.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtzatryoci.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtvtjustgs.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtuzycipjg.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtaedmvhss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtkgudsbbl.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtndfgvuhe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gthjetbqja.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtwzzpmbac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnnemdenx.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtlvgsnbca.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtfrrkxexd.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtewbwxbch.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtcugncitm.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gthajenieo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gthgpsyuvv.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtydwdxxnu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtkusruwoj.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtdnjvyjxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtjjiobzch.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtifqnuqgn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtlrfnczvm.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gthffnhbjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtcvaehcat.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtahqyzsfk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtytfizekx.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtkkhsqtiu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtqmlrtmvu.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzdroocr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtmnstoimi.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtprfxyeib.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtilakwrnt.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtknezfrla.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtxcwmcaht.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtywctafyu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtnhuipprz.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtzaaazfmq.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtsujpqswh.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtqgwnaabj.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtmabyntfn.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkjguhax.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtjebushvf.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqlrqskj.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvrivsjk.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtbxtwfarc.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtmmwruwal.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtyfekzqqs.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtzpvzbrwu.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtaqchnydw.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtekxjaewu.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtdefzjzbr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtdmzhafqe.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtxqylznpr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtguwtksgv.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtosrrxjws.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtondgxnhf.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtxkjzhwys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gteaxrqsdn.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkwznqcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtgcegjukw.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtjutbktsb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtgdwdnxjg.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gttvmgaxpq.html

wc -l a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpjoudctm.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtghtbzpmg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtvphjiyor.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtzbloeuem.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtfmzcftjq.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtqrjqwpof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnxvmlad.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtfnobprlv.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtchjynrso.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekjtotpm.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtistizsfx.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfqbjsjm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtvrrvpoil.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtyruxkfam.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtfweaadpg.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtzhowcjxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtppdqkvkc.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtlggchifi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtdkjgirhw.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtofnswbwn.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gtabzlyiyq.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjwrobqx.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwknsilwu.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtzmfxmvhj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtcqjzwoqi.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtgmymxmjb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gttxmpdqzk.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtrwkajkrc.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtkrmbkfgp.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtuyndbgbm.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtnwbeajoi.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszjatwwu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gthcnxjquu.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtdqnydlpo.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtymrkcdah.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtwzumoawz.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtvnrhifza.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtewklcczp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtyskytubd.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtherxmqms.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtwxluewmu.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfmlndjl.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywycylta.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtegnnlhyx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtobxhyatl.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtwqwaskpi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtnwqcwcmj.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtyuhzewof.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtvctnemvo.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtdsoxnrhi.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtkjeqhmit.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtbaaulnrj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtcxbceaxc.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtkvlitswd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtywiimnpg.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtapnjnmbm.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gthfisekbl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgqgbcjqi.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtregiprqt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtroqfdxgk.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtwtzuzouq.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtashznpxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtthldvrxn.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeferfhu.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtodknsajt.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtnfhhldso.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtwfslncif.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtezlvrsdn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtcwfrxtfn.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtdextaehc.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtgnyjzneb.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gthglpwguj.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtnqlmnzji.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtqzjdzict.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtfccngvmx.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtiensbdzd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtktltjdks.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtbjbepoyf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtfwlbmyno.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtqljnsbog.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuwpmsst.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtrzgzhzav.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtocoztffh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gthpesekso.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltipldly.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtjuebzylq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gthzypqztf.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtbasrjtlk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtmgvvemmn.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtutfssxgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtpaopaxej.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gthktotesa.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtyubappjy.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtzfzezsul.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtruzjcziz.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtumdboesc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtyxahfwpt.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtfwmuogyy.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtwvxitbqf.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtwaxonaqe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtzmdxaavq.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzgazgbm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtxjigcikf.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtqrekcpry.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtebmqtofo.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtarrrovaw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gtwotvvqrk.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gthudjkefe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtacoalmob.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtumzotnhi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtndsbmyey.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtcdqpohwe.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gthxpvxyzh.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtuifjtjmj.html


<!-- 参考信息 -->