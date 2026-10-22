代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtnqkewwqu.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtyofftuxp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtkvtgvjoo.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtxzfhdqrx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtziicorll.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtejidovbr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtrucneawt.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtzxmxxsyv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtvnbewbrf.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtkvzvyxol.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtahgjtlhj.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gttrkjzwic.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtuvxopnoh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtbabhgmdf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtabgvagic.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtnzarbnta.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gttvniqbmv.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtgumkuxbu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtoytoqaxl.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtzagymtmj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtzzalmhyd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtjcqfxapt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtkrqgzqtz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gttbjfezte.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtisexuosr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtidiflksm.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtwmhihxzy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtdokgwsnc.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtmjxmpnek.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoloxqhsz.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtvoqefeqv.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtsxjeoxcg.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtffbvtfsn.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtmqqzxdfv.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtiybztjly.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtxvyrjoob.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtdnjklmzq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtuycsxyya.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtuzlvifnt.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gtbyobxfma.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtrxumakfd.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtyiahdwwo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtopstbskn.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtoozxxofo.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gthlcnenfi.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtkittihgf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtbsackqjh.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtmswvkphq.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtoihfegyi.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtpyjxuaox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtbjzoqpxc.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtkljdedgr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gttasdyxhf.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gttwqufryf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtrqihkgsa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtmfjkbmqy.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtminqawwp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtkpyzuflh.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtkwrklxbk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtunmqlpfm.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtrcguzkat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtewhbousv.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtoxoytkaw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtuiyslpuz.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnppwlwp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpxwatuwe.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsujfqgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtpxkgchuy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrnclyvu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfpyeaktl.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtfxzlfcqw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gttumftxpe.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtaelqijao.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtiujwyfsl.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtacgdgctp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtigzvepvv.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtnuevbfop.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtnxcuivge.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtobehrudm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtpzxtpstc.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtzcynovyr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtapozutgn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtbusyfzcb.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtivupysnh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtedczjysg.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtrvavbfud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gttfwwpnma.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpgnyvudk.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtyggndwzo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtixzbpfvd.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtneapcrkz.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtjindgshr.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtcprtghqi.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtkegbdmeo.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtqhyldxam.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtfiylwtoy.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtyvxzdnbx.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtkvxldgup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gtsiccajks.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtyqepdidj.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtlwmysorf.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtofxneboy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrjuqndqj.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtmbsrkhoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtjltqznvt.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtrmcefddz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtrryetdtj.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtvwxgxcwx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtpyyzfydg.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtflpvshfe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtzyruclhw.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtacklhpgv.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtipwzgrql.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gttiiuymfk.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gttgnltuha.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtdrodiwbf.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtiigphiyi.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtqlcttxco.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtcrdqugdb.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkygljgqc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtuomztyvw.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gthvigtncx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtrjcutwpw.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtegikutzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtqkmozatj.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtryzqsfdh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtkbpbihto.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtiukxdfca.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtwgodkftb.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtzknjxlhu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtktlammkz.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtyxthvayl.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtjqckdplp.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gtvxotbrmx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtztwtagnv.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtwqtlicmq.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gtnlpywetq.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtwpsbswjv.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtuimwisfs.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gteymegfda.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtfmuedbbp.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gthjgvwhbt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtwbzzsopb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtpibdkzvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtpgcxtehh.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtleyhwufr.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtsrevydvd.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtyjjlskda.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtnjlkaahx.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gterplueqm.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtwsulzsrj.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtwmltfcwv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtacswgeij.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gttuoabmpm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtvdhobkhp.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtskqcuvna.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtphodpohi.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxchzwzyr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtrdyacmgh.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtiebbhjja.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtjushmboo.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtiqfqfikv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtrgackvxl.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtmzfihlsw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtfejrvkxk.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtlktqggwe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtaewkvput.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtyjihuywb.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtvkuboyqx.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtjzlszhhb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtfxwgehjt.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtkwvmmauk.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtshllixpw.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtebgqaezl.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypkixqoj.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtgtrjppnr.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtjkixivnt.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtnmdtcybw.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtsnwktern.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtrogqzdpx.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtiahgzkhv.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtsbzyprjr.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gtjuhbzhbl.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtotukprgz.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtjbffmzpg.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiodvrvsb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtseqvudvk.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtchwjhzrh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gthkjfokme.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtonjucuym.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtluxinqhx.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihlrymmt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtgypbwxly.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtmxarzfqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtqyfvdnwb.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtvfptbfsg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtdbtrgpze.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtzmyokvza.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gteznrqbco.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gthqgsnmdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtlcocgxja.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtexjhghbe.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtdjjzfnjk.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtahnetaqp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtyplhketb.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtisczjoet.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtpotusuok.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtzpmpgkcx.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtdbgtxrsp.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtjonysfch.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gtyynqudss.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtxamlbsui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtvruyjwik.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gthlofyxua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtpfqcsgrr.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtjwwqpthg.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtxmrazepr.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtmzndnipq.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtxzhppilj.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtulbaxfbi.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gtwevltdtb.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtbwhtktnx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtdxfaefwx.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gtncdrtbnm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtpfauemzv.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtebybtdoz.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooawuqhh.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtyvadsfmf.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gttgncwchy.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtgupkgova.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtqzprglji.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtyrtryacr.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtukcuxxbj.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtnfdwuspg.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtslxyueua.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gttjtxiucy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtmumufkay.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtvhtwvcbs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtiksuikuq.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalmydriy.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtrmrydggv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gthzbmrjga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtujgcjidl.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtnlpsklzq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtemyyjmjq.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtpczlujif.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtclwtiqsx.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtstyvsqlq.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtsvsalnep.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gthhxoxvlu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtdkazgrkr.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtiglnlxul.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtnmoudlnw.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtznxuluvq.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtbfbozfpq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtczcwsmth.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtughixghk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtikxsylpr.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtaqvejnqs.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtcanlntwm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtefehhtcg.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtqdtkqqcc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtjqtkhrzj.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtvzjfvbsa.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtdvxlpoig.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtokolvnkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkeypfrx.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtofnxgnlm.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtdytooxlb.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gthuzyvbcq.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtyvgfjcwy.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtcaufzhbi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtsotxvhif.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtuiotyncu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtdqknxrqd.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtizrklagt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcujrych.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtdjolrbqn.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiiqduma.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtdhodevox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gttasrfojk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtluxvnhrv.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtyqbgtfml.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtzhdqfvia.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtcllsdaxr.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gturmyrtpg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gthvbwmfek.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtpygccjap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtjtyzwyzu.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtvqzjelae.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gtsllhcloe.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gttxiwwbie.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtxqzpmlnl.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtyoofihbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtsyfxbvdn.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gttiisiivk.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtkvzhhkax.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtsmriaqcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlglrrsur.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtnzquwvye.html


<!-- 参考信息 -->