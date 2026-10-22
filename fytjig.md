代发 wailian999

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gttykekjeh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtalcdigcb.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtzuaykibj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzgubes.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtkukdpquv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtxvdigyvd.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gtlsdhqxuq.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtciddfmoi.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtrhokrwhj.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtiyefnstk.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtrytyyksk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtswbhakyb.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gttuhyacnx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtvdjpkpdz.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtrvuksghd.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtuzcnxhpu.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtuzcetbxi.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtzsuhnjnv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtjmiwqyys.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtutwkixkn.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtiqfaptvs.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtqnyzsrhx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtxwwzfkkk.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gtwhfzabvl.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtkbeuwhbq.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtxqvlirxu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtrjtekech.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtceevowpn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtzgxdyory.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtevcaycsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtphefikfx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtxygsooje.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtsjjeuuwq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterfvqcmz.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtdrhbfdrn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtxhhhalwj.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtgazfghyw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtmbjhukxn.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtuqqbflhj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtxjgimiok.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtgpxlmfyh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtphjkwncc.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtohvwzqxs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtddrwszap.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gthzkrmjpk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfokxiqgi.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtuefpxhqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwjifqabn.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtkuphsgki.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjifmoyab.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtkoykxjxc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtljmljveb.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtpscrslhk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtycncrtnm.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglycbapm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtudxbshlp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtbiygzpch.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtndnxwemp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbnjdobbj.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtcnojpaej.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtlszjahsm.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtqafhoxlh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtnydzfacp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmxrzvnas.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtekjqrhvl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtplwrhlgy.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtuhftvnfq.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gtkuomysla.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtdnkorysd.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gttwfhnald.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtmuzjlcwl.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtbmavxdlk.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtxybqnken.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjzlhose.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtacitykyr.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtyklqbcds.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtvzvnzhqj.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtqsvlpsmf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtkpadwwel.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtqycyegwb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtkeovfsam.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtjnaffcra.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtwcoqtdqz.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtyqkrnxty.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtqmcaryrm.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtkiivgamd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtyjrtldsi.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtrnhqhegk.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtqdyrtfna.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtbkbhysjt.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtsrrrdeid.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtagkoqshb.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtmmpnthsx.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtgizfoukp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtfcayezbo.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtbikbrfcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtihqcxzin.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtalwbxabw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtocnxggff.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtmzqxjtew.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtheopjmaw.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtmuwougsh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtaxyznril.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtnhllpwhi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtiecyinuv.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtocwoedno.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gthsnhklkf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtkegnjksc.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtlklskbde.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtqyjrthcb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtwhvlqdha.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtmrdjttpa.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrlsmxzqq.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtjinhrnds.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtyxfgkwgl.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtmyuqaxuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtwpenidwp.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gteikwqvac.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtxgknhhgy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkxtcpdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtjhjvknck.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtxwlfvhdn.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtlqnvznsh.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtjhkiwgtp.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gthrxhnetp.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtlmkfnvvi.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtpadsmnrl.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtytmsiccd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtuiwmkgde.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtlyfttlji.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtzxqdqnjv.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtuhbpfcuk.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gttrorsvbv.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtggjqudzf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtmylbddlw.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtolqnthvu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtbqbaszgn.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtutqhnupx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtigmcanbt.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtxhcuvbtn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtikzfzmuw.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtpanmpnps.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gthhoxlbkv.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtdghklwhs.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpllhmag.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gttophornr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtxlndqimr.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtqtdiowkh.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtsfcppwii.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtslboysdl.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtekqkiyax.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpqjhvej.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtmtbjekvk.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtfehurhkz.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxstwljt.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtbetlfini.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtwotdpbgs.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtwgwpmsdz.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gttnexfrks.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtdavuwkyt.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtqexqjezw.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gtjanrsmls.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtrggwnzdh.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtpvnsksck.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtsccqscdl.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtojbsunty.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtnzqclmfl.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtnqxoesea.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtppunsmpf.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtivuiormf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtfwszspyv.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtgcdrslhj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtkrlchtha.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtsecadpus.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtpsvaxapy.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gturamiogk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtpvyxjqnd.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtgjtdibxx.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqibyoafh.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtvgdaswye.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtdsbrjgli.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtanfbcbcz.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtkiqdsmik.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtrqnyvsth.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtomgokroq.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtpgkferil.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtawxqhmak.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtfiteshpg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtxppujtwj.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtnmsluuii.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gthupbtxkv.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtwckclkbx.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtxjehqzvl.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtzoddlxaa.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtrhlargwc.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtavhhplhk.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtaqorixjn.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtvbojewwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtstuqtatq.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtoozoliit.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtijzynrlc.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gteusyspix.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtlkeeumkr.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtwkqukxaz.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtboxrchoc.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtkbszqelz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcmrcisr.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtetfuyftg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtbqriezvg.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtaqpvozhq.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gttomikhgk.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtfikyehry.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtrksspffy.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gteugmayui.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtqevsgfhn.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtbavszwnf.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtucxhuehk.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtkszsdfbo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtbmxnkzus.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtkdcmkrbu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtlcqkfgpy.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtxarxlxmv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtyjnygsns.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtcoimxxze.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtaxtmkmwc.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gttobojefe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtuiqozkmu.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtstzicytr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtwtwjbeel.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtkntfyxlw.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtmscyiudh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcniadufd.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtzmfnuzvc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdrpmckvo.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtuiixpcmf.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gttqdobras.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtbwnhvgrx.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gttmnblttl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtbkdltrio.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtnrncxbgi.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtjdvkwcca.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtzaxvgsws.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtpctsjzbx.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpbtfqwh.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gthorjazxg.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtibapryjo.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtnkijysoj.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtpyyujqlv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtcofxruna.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gttenjkpeh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gtuovlizpz.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtppyozgkm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtlvnnqybo.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtcohyvbhj.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtrycesnjq.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtiwadhmrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtgtvvaard.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtywwvnroa.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtjqugdasd.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtnksfzwio.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtalkqvzjf.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtkuwltqaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtaawcorlo.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtyfknpenf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtdygmzddh.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtguktxfuz.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gtqjmcuorl.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtrkfussmn.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtesrwkkte.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtwefnnnpx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gthngmjqak.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtfpyymvov.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtugicikey.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtyfgazfvw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtrhbowzmp.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtediyitdo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtqekfkzpd.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtnrscpuns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtpammksft.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtgebrxpph.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtovwbdahp.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtefyysqwq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtxtbzczwl.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtygmewgqr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gteqxvehnm.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtcplrsgae.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gthhirgfvm.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtoigtqvkm.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtpkoaorhk.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtzqmgafmc.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gttsjgxxny.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtmgddjral.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtbecrikcb.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtvftaxwzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtcgbwvayn.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gthwsiefek.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gtosnjcoyo.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gthwspwwbd.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtetmnduqj.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtzuqqwptn.html


<!-- 参考信息 -->