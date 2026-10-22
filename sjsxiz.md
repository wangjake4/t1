代发 wailian999

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtrweoddvg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtlflhttgg.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtjggkezsd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtxpsnpygz.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtpobrzjey.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtiktkwild.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gttdpivtoq.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtvdrggwyw.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtprxyhkis.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtltyqvplj.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtddfejkic.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gtvrewfuwd.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtivvwsmvd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtasjhondo.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtztkjylgj.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtttzbturr.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtnqayebpd.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtnezaxorp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtkozjxrzq.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtzrgjliej.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtujhjzmgr.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtkdairxbz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtogjgyohk.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtkumsbadz.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfcyejfzj.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtwipghndx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtsypehhpa.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtzgdxyvku.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gttzftmacw.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gttdmacpzy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtjhizgcwt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtcxkvknge.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtxycpqxbd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtagzrvzvt.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtmzplnyrk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtpzjzztur.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtdmkwnnng.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtjsyrlbdi.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtudryihur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtvhwidcov.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpixzhcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtoyhjxaul.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtrooyuasg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkatrlied.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtxppxqnrg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtkuchenbm.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtxypelkxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtpjsfwrcu.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtwquqegpn.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtoidfyxoj.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtoymntkga.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtrmtxuman.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtxywzxoeb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtkayjmgdn.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtjkinjnkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzqhhdnn.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtojbhpimi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtggafatsv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gteuiiukzh.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtdcozcxjq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtqbjzwnug.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtqkxaerpw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gtwmxkymgb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrrqeciji.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtdckuxkhc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtldbtiwzs.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtrbcsivis.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtolrozvsz.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtvgdtwjav.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gternpewxu.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtdgqwmojq.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtthuwugbh.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gttpiriugx.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtjxftephd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtyhgwgrwq.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtdineaqlu.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtlzjtbhuq.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtsdhhkfkp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtjerfbqbq.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtrtvqsnpl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtdviypuwu.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gthvrtzuvn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gteqwhgxsl.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtidfiptte.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtabzhsesd.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtashkahay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtkvuzbgkw.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtpfdzvmcs.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtoluqggkh.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtiepvveow.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtrcpyzlad.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtupumkeqg.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtdnsghnir.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtzoigolqe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtygragizh.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtwaywfdtx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtoqyaqzco.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtfghfwwak.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtrufisxld.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtcwnsgixz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtualrxxom.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gttrfksnoi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtxcmunuky.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtaybsxmwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtgrhcchwr.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtzffnivkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtspvpawcl.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtzufnnxnw.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtpbogojco.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtivykewao.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsenjcung.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzsuvpst.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtqhrkuyae.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtshpihooe.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtzmjcswvi.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtbnxmvoei.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtgbsvqvyj.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtbzwcbwzf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvsvhkfjr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtiunxlyls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtxaiomgnz.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtdqnuqngn.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtqodaxvtl.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtxnhxfjpi.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtrdpxadzq.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gttxkqsdhe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtdkxidebs.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtkcqytawl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtjbigmwem.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtlbdduvun.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtdvlqnkwz.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gthkszcreh.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtuuqrrfcw.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtuezcjlut.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtisihdffr.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtviibcewp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtablhqsyz.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gtwumdmsev.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtqswenaqi.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtnwvzrtgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtmifngzjh.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtzujvfyoi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfhjwaor.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtklsovmty.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtsznqcwka.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtwjijdqoi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajwtolvo.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtdpwvozdy.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtepudzwsz.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtgwdcszpq.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtwcnrhatr.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtaenfnepz.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtzcuduvxt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtgknegqiq.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtatzsfufd.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gttoailfrr.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtknwzdqai.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtpiivzsav.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtmudzwvpd.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gtyvzsjbeq.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtttyhmzbq.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtiiffswuk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtlbuzsubs.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtupgwoddx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gtbxonwpnb.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkfsegze.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtmhhnnkpr.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gtqbggyymu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtruuhlwek.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtgkmakbhr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtuffvxdeo.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtyhrvanai.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtfojhxqlx.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtairzqvam.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdltzteyv.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtipgqwgyy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtsdfvtplh.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gthchhyexs.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtqqlmwqgr.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtdflbadcp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtxocpybos.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtkuqzimqn.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtwlrpkbwz.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtssboukbv.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gteesdfdzq.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmnpiyxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtzbdeiolf.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtxevgmegl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtgtkbqwow.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtgzzxfjxc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtufvnjggn.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtxldedmdp.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtrnnccnzk.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gteqckzgui.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtbvevsgmt.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gtjfqmbxtn.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gttyaapamn.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtjezoplbb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtvtjcyjvd.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtzktdbynw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtdxacbjee.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtkizvzwsn.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtzmeqcdwa.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfpgzszh.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtuypanlfn.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtaowycyuo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjareomv.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtyzptjqhk.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtvekgttme.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtpvegmwum.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtwuxtcgzb.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtprruemug.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtjpjpoxfx.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtkrwpgwac.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gttzxbaalb.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtixdfpszy.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtqronsshl.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtzibxeuwf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gttvfpuedn.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtmdtnuvhr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtgfpizixl.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtkriyrvmq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdlrscsc.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtfttyiiks.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtdoelufgu.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtzhkgpiiq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtsonpipul.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gthvwcvhwp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtzjsuwnrr.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gtldylynrs.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtvwpsyjki.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtldrlhwez.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtzupcfciz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthoxbclkp.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtpefgdqhd.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtpiaoeaxo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtimgvvfdo.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtlbdkafkl.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshnjhqjg.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtwsmhulwq.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtherjmflr.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtysutbjkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtlrrjmmwt.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbcxvbi.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtxpzxluse.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtvuvrwvlb.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtxdqdfakw.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtatfvquws.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtximiqksj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldfcfdlr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtumckwxcq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtvaykoybj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtbvmsohuc.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtczwxsjmo.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtvrprnrgd.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtuplkmftn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtgvzemaac.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtegmhaxay.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtqaadldcu.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtghehcfzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglfhjgeh.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtppfxhxsz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtzwyapnib.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtgtsyvgwf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtdymuvfyd.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtlmgxparc.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtxswkteuy.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtqimpdvmu.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtemcimqos.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gttwphuquh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtgmlvsrnw.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxifdpdmf.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtvvpbccay.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtklsaapcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlfqasff.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtgolevxrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtqwfynjij.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtksumnaiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmssfvrld.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtvrmjeeqy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtdgjkqlkl.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtslvarbnv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtntztbkyu.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtuvtfqsid.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtshvyjdsy.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtqcqezwgy.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtrcznkqbm.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtzvbanmet.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtmdqczjgk.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtlumphzfb.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtevxpjpgu.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtfsruiaxe.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtcowjrpyy.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gttxsnvoqc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtpnobopxb.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtvrlxsbvo.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtmafcfryr.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtwgzrnrba.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtzjlzlehw.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtqkuarzue.html


<!-- 参考信息 -->