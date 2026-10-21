代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtntlmmsrf.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtjhhcaqux.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gteyvbxhxm.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtexqxkvnx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtepplpdoo.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtdpwrbxat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtvtvckklm.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gttlppfznd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtbgnathae.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtbbmibgfu.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtwvcobhvj.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtsyjrufah.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtivbqtkpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gtfwlbrher.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtnfiqbhmg.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gthlfqhkdw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtxstnxjsm.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtztzqjgak.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtwivkgqxq.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtzfzsixes.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtsjxfvffu.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtmsduouoz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtinyompwo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtswflbehz.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtvwbukfse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gteczuyjfz.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtfeyjlrvc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtipuedbro.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtqptvkpnm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtwqtgwlhw.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtbqnzzuyg.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtdelwwdcl.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtgldxzknb.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtwsvmrqpr.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtyxmwever.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gtukglpelv.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtsssfdaeb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtirvqqklm.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtoaabwevq.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtcioicxkz.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtwhnykjkv.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtjichsamb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtaclzrvbd.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtsvdskoxb.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtsyuwgwma.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtdeyicsib.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtoohithrr.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gttsxkmbak.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtbraiajhq.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtuoltgjhc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtgvfhwytt.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtvayesbzx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtmtnlnfjg.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtobftxkll.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtdqinvuky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtatxchwvy.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtuzcgfphb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gturwghitj.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtmncmepgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtkyhahqsv.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtrbzxmdlt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtqiyyjcta.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtzyqfieog.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gtmxuqtidv.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtfsmfohri.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtvhhflsxn.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtnpvxwphu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtqtcrcrsv.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaryambj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtztoeniay.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtkwvnjfmb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gturkpshga.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gthfvrkpxy.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzgcwlrvf.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtzjlqjsag.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtetnxqnzq.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtuuwetdej.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfouahoi.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtgichsyto.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtbbdlvdsi.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtdlbwauud.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpxsgsyo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqwhxeqn.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtygmqlqkj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtczknnxom.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtdylsdspr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtgxdzrswz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttswgmhrp.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtmdcoisjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfqftokfq.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtujkekkzk.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtsoerybqy.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtcnzsspuy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtjfetnbci.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtwudguwht.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtbxqrwtab.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtrzfehlux.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtzxtkpyyd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtrcdcbqax.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gtevsarfoe.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtbfpsdlbk.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtuygjjjcu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtlbsjjaiv.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtkvglxssq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gthocnbrhh.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtkvungfye.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtydyolbjg.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtbqjutlra.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtjamcmkhs.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtvhldjugd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtxcachwov.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtngtjdyfs.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtykgcvgjw.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gttxmbghdo.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtxacnpvqf.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzneomcp.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcknsxwmr.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddtfvxkp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gtmhquvunt.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpblisvc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtipsxseni.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtiuudxmij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtawwdllnm.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtagowwjju.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtfymubyfn.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtuiokirru.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtijtmizza.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtpmgiwund.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtgwiixcup.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtdmrhhyki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtlqbteprp.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtwurmsdpb.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtqezyhjih.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtkfmcnepu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtlzwdcycy.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtskjgogqb.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtkfyhinhs.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtyxqzobfk.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtfthlmpxk.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtitadugpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gthvnzrqch.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtrgbcqcib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtxlvjsadl.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtbyeodwzg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gthpvsoyaq.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtmrtujxas.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtmbfzdwxv.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtnzmouatl.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtlswfmzun.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaxgozzc.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtrnwtcbjv.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtbyskwzrh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtpgadtqnu.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtmaetaqlp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtsepkrght.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtmosueupl.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gtasdfhfxm.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtbwopuknd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtmtugoihw.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtszwykioq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtvxsyjlhr.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtpmlnuqna.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtgnxgsmuk.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtuasyhrgh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtrpkdiszm.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtjymqbvjp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtqeyzffkg.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtjcivdqyw.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqazgzsd.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtzjivzfwn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gthukpvasd.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtplicydmf.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtautwzmem.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtapilbxam.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtxsvsjtgy.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtfatjibsx.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxolgcevl.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtxhecmsgk.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtmdsddfos.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtoqxjcugm.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtmtmiwjdz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtyddtszqj.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gteupuojjx.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtgrxxsmoq.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtdszyvaxu.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtgwymjjby.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtrjopubab.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtlsprrzrj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtmklwpfkv.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtmrdqhryu.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtaonjmdej.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtxibyugnm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtxbiwpupq.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtomlflxik.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gteqeozypd.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtlklfzrsr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtsdpqmzgj.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtczrfygjm.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtaiewxpeu.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtjzflsnsy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtpwswblsq.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtkwytotlm.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gthjqpslfq.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtdhqyruri.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybonvrdi.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtnihnlrla.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtqfquvtqk.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtkdfjsblc.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtcqpxvfpa.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gthyuogzhr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gtdofzivqx.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtuaccpiaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtjtgmicmz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtzyfwbtvc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtlbjyanhc.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtuxpbztwt.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gteykbiuqt.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtgwchppan.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtldjaepdu.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtakyebucr.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtiwgzmpzt.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspdbuhts.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtwewezqvh.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtrvqkwdil.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtgtvhezff.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtgqbdrlge.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtqflxoahv.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gternddwjb.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtlpkdhnew.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtophewnhv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtrgvbmijw.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtkzzdemxy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrevyrqhf.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtndvqfkrh.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtaqndjgar.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtuabcpufc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtqkityxdh.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtmcbgyzqi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtrfkqjunr.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtprgtawlf.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtkwbpekiy.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukptripr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtmmnnuwem.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gttwvkfyep.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtbrioegzr.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtrgdisvqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtotxtryjw.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtcyjqocke.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gteeiubtcp.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gttneyjfnk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtjcatdbax.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtsuxbuepf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsbtdrkg.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtuardjupw.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtoogcckpg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtoecadsih.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtsdpyzbxt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcnsqyuzq.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtsxjawdua.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtrygipycy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtrtovttop.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtnektefwd.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtywzgczgu.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtqexcrjqk.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtcukjxsix.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtvymmggnp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtvmlnssfw.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gttqampvwo.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtjjwcfvfe.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtjimqhrsb.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtaablxxeo.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtlkdxwxlv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabgbvzcg.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtqvpbtkhy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtqixniwit.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtytbomhdm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtcgsaiyer.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtxmrvclxi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtporebvov.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtdsnlsams.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtoxaxkdvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxzjqtut.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtzgvfuquk.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gthpencgyd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtewzzhoin.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtbblvtvbk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtfptejtev.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtmmzlwdbf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtyvakufhf.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtskjfjmkl.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtwaxbmhkv.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gttsamgtsb.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gtcftjmjzz.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gthbklmueo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtalqnlgqw.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtrafbdojx.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtcnnxqodl.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtvbwsjzpf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtsusruscx.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtcbddmhbv.html


<!-- 参考信息 -->