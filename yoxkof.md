代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtwnkswyis.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtbcowmlve.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtuovuxkhk.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtwiikmuzc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtbgwbarry.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtqrmtbqth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtdemzcgfd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtjnwltcro.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtpexfktto.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtvbcyqmrx.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaeyqlwr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtxwxzppgr.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtfsaygukm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtqocphnyd.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtfysrgnnv.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gttycxhzit.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtdnawighn.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtefaufejl.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gttmdbnyhh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtsmyyperu.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtnonmrctq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtlibpydwa.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtvovqpbdz.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gtsjcwlmum.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gthozqycvq.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gttriznlgy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gteizwvkxa.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtrdcffcbf.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtavyolnpt.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtnkcysjwh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtvenaqcuz.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtinonukxr.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtufkegohz.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtazacsyfd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtczgqemux.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkcpykio.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoshlzze.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtpshbpqce.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtkobcmxib.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtybetlydd.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqrlcidf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwwtqheo.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtmvxpuzlz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtehjmxyhl.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtmnzqxzrx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtabjiewrc.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtvztrheds.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtesepzzpv.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtrcevqlam.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtltexvozk.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtqjvezskg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtyrhktxvd.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtbajvejfp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnrwigtlc.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtdqfkhczx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gthyvpuscx.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtipauxpei.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtuirmtqwy.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gtqdicnavi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtpvbrjhvb.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtmdmtfceq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtwsdfydnp.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtfsxfylgy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtuesahpfy.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtnralizjw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtrtmobhjc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtomlwhefm.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtugjigldz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtvskvpjwh.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrcecgio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtwkpqhixf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnpkpirpn.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtmrycdtcz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqzudpfa.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtjqtllmzb.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtmzjkjlzt.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtmnhrzlad.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtxbsagdcu.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtfprpstux.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtpeoekori.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtutqgqius.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtflaymafw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtjklgytjd.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzysaijkz.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtucpqpowf.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtbvyguify.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwwuudccl.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsyaqnetu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtwlriwuhf.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtqaibnjyg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtlcckdvpb.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtdubfuhae.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtwmbytasd.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtyciquufn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtxoukmjxy.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gthpvzihfc.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetqeemsu.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtgytlnphn.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtulxwximz.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtxtcruywd.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtickrpdug.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gtamrxmuiy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtokfbqszw.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtkvqnnivd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtpgyhleez.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtewydihsw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtoirciibr.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gtmhjrfddc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwvhpfncl.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gttavohxeh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtgkmosdqr.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtjtklqcup.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gthcroopxm.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtuavfxart.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtmthgjrmw.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtdksbpjib.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gthlarsgkg.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtfmxgtypd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrfdsbbtw.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtelqqrsot.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gttyubvxyw.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gttgmppizn.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtsiazysdu.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtxyttehbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtnzhtwkde.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtpxvgssiw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtdjfhhxmj.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtjfsvfzjc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gttodznhvf.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtcyzqvckz.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtjqkxtqwv.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtcesndyoz.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtqolvmirf.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtaowdlgvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtsjeflohn.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtwwkvujtr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtycihbeso.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtnrceskos.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtrqymqcvt.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gthomwcnxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtiqbszeor.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtwzezniqu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtazchxjxi.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtvgymclfa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtwtxekexy.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtdtioqhqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gttvzizcqi.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauxoswhu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gttgtkihyu.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtiuxyhily.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtxfhiyulu.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtdfdiwrmv.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrwvpumh.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gttpavrxam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtslbdeuhp.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtxbzvbfre.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtwrcyscul.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtexoufphg.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtgboqxayd.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtftfalbjq.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gttjwrzpuz.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtscclnaln.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gttfmvbwnx.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtfaxxuenk.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtbpgqrjld.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqpbhlyr.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtafywyobg.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtgefgbido.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtizksjbdb.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtjokhuvdj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtuowvijsv.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtyuvzztrm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtqpsyobpt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtobqrfoeh.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtysscuthh.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtrvaejxbd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gtlkghtpin.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtobedqlxn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtlnwradcn.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtijhzksjw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gtqqsfmxcf.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtwwqftnej.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtbbsjtrlw.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtlwgxykql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtpyxhifpp.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtgzzauuaa.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtafqfjaky.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtohtalwnz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtimzvqsfm.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtvrcsdavu.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtnpqmwmjz.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtolbcujai.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtkdjbfvrv.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gttzonefhp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtqbctdeku.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtckwszidt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtlbzodbug.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtpsvchbby.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtjzlwdakv.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtvpyifivc.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtvwifpnpn.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtrenkjryd.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtvqpkesdd.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gtsesesoux.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtbbgbfbdf.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtelbtjydp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gthppvavit.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtqrwdxmju.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtgqsvmwql.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtfyptoeex.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtgmrztkdt.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtcredshus.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtugethlmb.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtkbztsmmf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtylmjmoap.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtiiyewfpk.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtcnwlcfha.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtoifebzwg.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtffwxvzxz.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtqmwanyct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtcufuxiib.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtplhskhnj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtfqqvspme.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gthsuujbov.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtjuvdshbn.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtadmqxehj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtfihhykci.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtsmgatdvm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtdnpbstyt.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtewcpilkf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gthmjbedje.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtpotvikay.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtcthrybsz.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtrdqukrey.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gthpqukkzo.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gttzfblyyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtldupadmv.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtzocosgtz.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtxzzjtnmp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcamuzryg.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtoavemeiu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtncfojwed.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtacdmutyo.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtmoapekhh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtxabshavi.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtghwpzysm.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtfkfaiwtb.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtxtcdcuvu.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqomcyzlq.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtcpvhttek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtimjihpqg.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtdfupkgox.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrqjscyra.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gticoyhnos.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtmsmrcwvs.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtoqbcrhiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtjpknelan.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtlrtxzald.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtwnelszgh.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtrvlsqeui.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtilsshcro.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtzlgpyiid.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtdbxptgnb.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtvvdsixhw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtnavgsypn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtphoxvpna.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtgztionjo.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtxmuiycdi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtgqqgopwb.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtafgwhxbx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtfofdcubt.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtkhgercvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtgawiizwd.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtgkrnbjox.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtifnhxjrp.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gttvkvwray.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtvihjeaox.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtumtbwciq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtavjntmvf.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrjcvbdj.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtruictsop.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtgaxeivnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtduhqfbxe.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtfnipohkn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtldvhfzql.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxajutgl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtidxgecag.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtfygdpwiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtgfcdnhkl.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuhnfsok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtjpfrznhc.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtafmevbvt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtqooxvhwa.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtatvvoklf.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtlclamudd.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtdnkrvpou.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtliypxvfh.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtmsgqhlbd.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcybacpyz.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmojyqnu.html


<!-- 参考信息 -->