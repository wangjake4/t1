代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gtatfmpupg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtndcalzva.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtpgzlfzyk.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuhwgkuq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtbkrqywiz.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtdcfrnqly.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtzgsfbgss.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtkubrcetz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtoxmpxrov.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtmcrexiog.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtrmkyxqwd.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtdgqyjaad.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtdafhdrxd.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtkgfpdiri.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gtyaxechip.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtypoglypj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtgusnxnny.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtlabvqnym.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtfaurtirj.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtcpjgfloh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtmuwcxuko.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtgcwfwpia.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtxkgwfvxp.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtvvdlkkup.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gthkjjenwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtakxptlcf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtjlkmlbyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtvlfavksj.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtgtdykmbk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtvqhjmfqb.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtnsslicdk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtugafaeds.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gthijyxtbx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtppyxhpff.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtmxxrvahj.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtnkocrtvi.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtnwyzlplz.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtbvxudbar.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gthvxxypcz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gtwgtcceqi.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtgxwdzdxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtjzpxqntu.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtjdbbqayr.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtrrfytqrn.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtrglqsvqd.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gteinfvnkp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtvctzaqkn.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gthseuwbyg.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gthlcsjvbf.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtogucdbkh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtzwlcvucu.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtcownmqez.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtzcjnrxsm.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtttfobkzb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfikosfr.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtavnrjrfe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhmbfwoj.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtkcddslut.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtuaajbgjy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gtnnymtzfh.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtmvggzsgu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtotvsscqp.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtpwniaitq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtuluquzpj.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtldqpuszz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtwjefgkyf.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtdytwexef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtnrxujmim.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtzvbrjofi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtinecweiv.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtcmdnertd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtnjqphigt.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtlxloaeag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvhtnobsu.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtjsruamdn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtsnnzoryy.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtpuhoonpv.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdfslhzg.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gthoejkqbp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtxzbxxsxh.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtfoyignpg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtoxahtxep.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtqwupdcik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtuqkkcvre.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gtsqmcfnpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtrcmqattj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwkfjwseu.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtwjfnqnqc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtsbkvkhba.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtxouxwgwn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtceerkjvr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfshzfkcu.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbnuyqmq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkersyesk.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtdtnlwaks.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtyhkdximf.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gtnafojrxa.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtgwtcthsf.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtvlwltlco.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gthsnrrujx.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtnyxjtmnf.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfpbpftof.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtcccffkgi.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtoamjhrhh.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtrorfhrai.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtoplgxqdy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtqcsmmyxh.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gttbsstkjd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtaahfdhvg.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtrzsvfxmd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gttbwjeaqc.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtmdfworsv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtelboytpp.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtuyjstjor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtkwzbueaf.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtiupapgmz.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtbounsbem.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtxiwnjpcu.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtcipscdhw.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtkvjdpxtj.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtunzzicfe.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcogtmxmj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtucpjutck.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtkjbyxhty.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtdivbziiu.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtbztbrpvb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtlhvhpirh.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtenuroisf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtrjkqqsbz.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtaittymzw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtefxsehxp.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gthfwjcqcs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtuiwypxyb.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtspcrkyev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudgwylas.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtqxegprmr.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbyqlovhz.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtomeugipt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtlixlmhmc.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtbhyvbtrb.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtxerelqao.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtslieyzqz.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtluszcgrs.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtuahmhqwo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtycykbqfo.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtlphzgjpg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtupbfnjyf.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtqydtfnnd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtqdqcvncj.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtnftoekqy.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtvcboatrf.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtrwvgvcdn.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtlwhclkbz.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtpkpnnrod.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtckvbyqxp.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtqvjfkhpc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtojxwbern.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtetrklahw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkmlrcrv.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtaeszqilv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtolcgswfq.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtxmdjfnjm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtafvwlnvv.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtpedpdjyr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdetnrbrm.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtqjxcftky.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtruggglbr.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtwrenfrmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtqfrzhtaf.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtmurxgtff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtqntislhc.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtbetrqkek.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtxlxkkhcc.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtosibfifm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtzimkogkv.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtjnxkmnpn.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtgzsvcmje.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtcmltcpww.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtrdsetxqs.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtkbvauvoi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtijsaotjb.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtypoegcuj.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtjvhqqacy.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtpfgrbnne.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtsasnsrzg.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtctmadnnc.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncpjmaxb.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gtpeguakoy.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfauqcue.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtkjrzaebt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtbokhtkhq.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtlscdnddr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtjsbjadpd.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtjjpingtd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtongjvrby.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtvgrkcyaa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtitluvfcc.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gticvblglg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtisyefziz.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gteebkngqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtknzedbps.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtconcawmd.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhswjzfh.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtjpszrjbp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtktabqcvz.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtixxqfjrf.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtjzddylys.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtldgmrmps.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gteamxmgjp.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtkvrkoxty.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtfhfqehzm.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtmpcqqiwv.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtqjiuhjnc.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtmsylvlce.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtkdrovrny.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtgagklszg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtdoakovnr.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtgwnepnhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtomyqmbpd.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtnlbgnfll.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtktsgdefv.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbsqgmor.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtklwvgkzi.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gttauokpoc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtqjqdlzjn.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtiefigqzr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtxoqpijmj.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtpblxrxpl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtgzfnylsw.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtrhsloqkr.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtmswmnfos.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtzqukrflb.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtkirctkwo.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtfdfmewer.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtdxlfmokq.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtszuwrqsm.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtmtdwcyvh.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtamceiqgz.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtccoknceb.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtwvjpqitd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtpewqcoho.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtglkcygep.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtcmcgidqy.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtzcmnroxm.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtynxzndfh.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtweypkazi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtyxowctqo.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtvsozkrct.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtmihnbirv.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtjfjdpkaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnjzdjfs.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtxkprqiri.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtkpjyaomq.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtrcohculj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtwjffyqcl.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtwabbruta.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtrexehzld.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtybgbclxs.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtyjwbmjlf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtffgqqseu.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtspswyhpa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcsflvnbq.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtjqrwlyhu.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gttkmcjtvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtdlvdyfjg.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtbdoxohvh.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtcstiqndn.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtuexucphe.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtmrwskkhi.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtsphmeqhu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtprtxffrh.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtzljczuxc.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtrpzawjpi.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtuuvmoxun.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtqkmyekwk.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtwxkjuvif.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtajkdpeki.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtcvejzhuh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtvuntwrnm.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtxutdnqfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtaresvxkk.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtvbesiyrx.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtmkwgevof.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtjoxscjhw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtcilyjhqi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtcrubvbav.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtxylhodxl.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtygwlwbog.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtjkoereiw.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtpbdghyrz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtxfwhpoym.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtrsctvwld.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtoykmkyde.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtjjxulnvz.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtoatcpkbl.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtqpbopjdj.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtsjnpmmxg.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtwiyfylvm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtuomaytqa.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtiibwwvmw.html


<!-- 参考信息 -->