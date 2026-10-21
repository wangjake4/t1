代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfcyagrh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gttccxahbs.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtikprzmgh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtfakycnes.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtpbstyati.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtehsfinpp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gthiymxtrz.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtxciepulo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtkrqmmaxk.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtzvwjepfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtofzaivys.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtqdymgspm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gteuqccihk.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtnvvnznfv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gthstsdaop.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtbsvnjwfr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtwghorozv.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtugrtcnxh.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtfgabdopd.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtlxiuoczb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtybjhyxat.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtwupixsxp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtubeibdof.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtqzfgiffd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gteyyuguvx.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtlcatngfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtcsngqrji.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtuvkcbukq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtpsskonrh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtoijvbdgn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtvozqsidy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtuvtcydpt.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gttywlwkll.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtpvqmjzyy.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtfayuevvk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtkrqwtlgv.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxfasqno.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtnwpejpxw.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtwemcfbww.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybseqygx.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtusawhars.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtyasrjrkm.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtllsfolxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtpoytsgka.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtgleorynq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtxhekmwnr.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtkradhmtw.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtfvxvkaqr.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmkaakxr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtouzwprum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtpmqlpzzw.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtrucktwep.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtjcxvmoyh.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtrfoxkvyl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtochiydbg.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtelwltydl.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmonpkeoj.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtzttguugp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtzdqvxblf.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtpoqhgphu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtjhgcalep.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtwzeymyik.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtgxrshqqe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtwijziesh.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtrcecakxl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtoqeylfso.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtmawknbsi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtiudnuuwo.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtqvtfukos.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtsxohqbwf.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtwwygvlnz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtmydauwlz.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtthwrplmh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxanyjlwk.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtecjmxelz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtacfchdnt.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtoicudvir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthvjltvgk.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtkforcfxa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtrzruopvj.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtdqbmaxeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxbyuvhas.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtwqhooifl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtnylffbnu.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtsgrxuniw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtqqcayzqy.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtddgxrtpd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtycxktqmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtcjilgdfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtoznnfuhy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxcuhxsjn.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdoclnxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtcftdvuqj.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtkrosghhz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtqadbkujg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgomklmpn.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlawkmmb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfznrvrvp.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gthxyrisev.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtgmbcpovu.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzpqlfto.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtiqhyyzxq.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtxlunjsvt.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtuzvfeqqp.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtuqjnchgc.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmmepyhu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtcpxrcyac.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtuzdvifcl.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtxxjionfe.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtpxjpuxjn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gteivlbpsi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtfvmnykxu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtznifvwcx.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtccmvslgx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gthrlwdryl.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtaqkvwdyk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeewpmlq.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrfkqfap.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtnfjhniim.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtnavlhqup.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gthtsmxser.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtvqsxgxol.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gteufgsymd.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtqtdvxuil.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyhevovi.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtvekfcqkb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtkgzyliuu.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtmnvcsuls.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtcubgmctb.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtxuclexhf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtzznxcdpy.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtmrtzpnay.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtkocujvoq.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gthczfzpok.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdavmpsuz.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkkpiywe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gttniyylbw.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtmyocgizf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtarqgbfap.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtsmigbeot.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtkvqwquaj.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtiavnhnic.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtiuevsuvn.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtqrphuqxz.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtecuzeslx.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtczihgbca.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtgodviadt.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtldsswbid.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gtantvbfwy.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtnneafmdp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtovbtrfhb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtxzwrmmzs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtzyplgydy.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gthjssdydq.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtxbmarzdf.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtvrikzfin.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtmbcklyex.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtfslhzryg.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtdqfxeaxh.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtqygrebuf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtghwzxvnp.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtzsqjvtrt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtdkrtctep.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtlxsbsxms.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtmnwwtnoi.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtbjdkuzqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpofiheh.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtvgwkqsrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtdalzlfdm.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gthustzkfg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtbmukbmhz.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtjrpmtjnd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtwqggnqkg.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtxyfvawvt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gthbfzddlw.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtqdndgmtx.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtpxocakcw.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtofxhpqww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtslwigtgw.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtuzyeawxy.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtconmotjn.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtjwlzbjfk.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtjcjocffi.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtfdeujvgs.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtnwmkorcj.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtzixrwzmb.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdjhnyyb.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtgysieuvl.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtssxmwmis.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtigkfzzxt.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtkudugmod.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtxutbrbny.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtvapnwiis.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtscqvpjjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtcmjnoylv.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtmorielnl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtswruabhm.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtgyygbdim.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtpfftdubb.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnxnulvu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtssvkizlx.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gtzhjgvkru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtapfuohgu.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtdcqrflya.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtqyrvtlat.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gterdbblrp.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtnxbvtuwn.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtiwupeque.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtnspinler.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymlbrcew.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gturgfkypv.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvohaenm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpacrktd.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtfeldpdrm.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtsfprcbud.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtuoohqmrk.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtwvbxcvtp.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtasthcwgk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gttizzvbln.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gttrcznxqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtabjkthel.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtttofnust.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtpyonkhfm.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtcxpycxwy.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtedcsyzdn.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gtxwvbkpve.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtilljldhi.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtrvhftsqb.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtyaccsqjh.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaderqjiq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtusbgnnvg.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtappiftky.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtjhkbbvfd.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtkyjtizhy.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtbhemvula.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcustdxs.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gttybqpaig.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtszghikpy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtmdcuibjy.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtphkkpycr.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtakvzdegd.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtzbbdtqht.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtjmlcyoyc.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtkmoidyxi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtkufbiqeb.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtfsagrcem.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtkwgfglho.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtkcpkpods.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtlphxqwdp.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtgmxuwaek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtnettklme.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtsxnxwmwy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtuneohcra.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtkjomnofy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtjehzjwsl.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtxmxghjhj.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtfklydlxl.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtatiryscw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtolzdfbpx.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtombuurgc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxplhesej.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtfsdopvqi.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtytyonmuf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgviypjrm.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtennykdwo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbvmjabkg.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtklvajdyw.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtghjgbbsp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtibqqhaje.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtskjmusgo.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtjoaknbxs.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtiuosaonu.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtheufypzo.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gttsorwhbh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gttuipuveh.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtaswuonnl.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gthofmvfva.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtrirclgho.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtszuaavmp.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtzmmbsaio.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtiyiwdnvt.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtutgabfbw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtwyuvfccp.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtycxksntv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtqcyzofdb.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtobzskcje.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtcvfsfzgh.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtolugdhuo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtixcvcixi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtdqhtojea.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtgxvwgsvn.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtmbhggmmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtarjneoiu.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtmufdnqzc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtljgssqew.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtrvtsylxa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtoobfdkmk.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtlzggxysf.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtbgracyww.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtnkozujrp.html


<!-- 参考信息 -->