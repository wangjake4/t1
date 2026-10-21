代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtvqdxxwpe.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtwnkctkgg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtodufrfel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtlbaiwuih.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtymfqvmxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtuquryxxk.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtymtzvvfv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gttldoewko.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtbiynakdz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gtuphinvmt.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gthhjndjie.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtcejppffq.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtubparajx.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gttamupgzo.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gttxlgihqm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkooxvsv.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gthnfueeab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtutpnbbgd.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtydhbkdob.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gttdpeikix.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtewnkxkwp.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtexzrwlqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtsgddaeaw.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaucflgts.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gtlzeojexd.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtbzzmqnwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gtsdvcvqaa.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtnuaopwpd.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtagbbmnbe.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtdswjmtwk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijuckrlx.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gttnzmwefx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtdwvncfsh.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtfthwabqq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtylrohoym.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gtuagncipo.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtlajawpzk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtbabqlalc.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtiznyifco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtbdwnnrsk.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtjneycamm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtwehlutcc.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtwvdrhjfl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtskfzbfqi.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtbzgmpzug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthlsoogzg.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtavpqhduo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtgksqckwh.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtyjvbpyje.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgbquqfj.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtbwxqeqfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtwcyrhuxn.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtheihbqrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrsezixnh.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtwbtizkdr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gthbhalvue.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtqaofquzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtgwobnffb.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtsniyvjbu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtvdmoezwk.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtcpfstdkj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtungmfcgc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthwtnrjnr.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtbfdtrkyl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtyixatxrt.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtdbmmoubb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gttgxclgmd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthftszgqj.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtmnspcsqk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcotooltv.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtuvszuuls.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtlkaekwjf.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtdjpowmyw.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtppoppumf.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtxfgstesc.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtseokpdug.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtzegxwyhm.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gthwosggvp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtkikqvpbw.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtmyepqnfo.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtgykogsba.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtcfgqrqcg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtfxnuavow.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtxoijflhx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtjexwrxza.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtxgxkglek.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtrwyzflez.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtvaeldolr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtvvofqjvu.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtjbudcxcy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtduvhnsdx.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtczznqhxu.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gttdjbefbl.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtpkwczany.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtlvwtgwie.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtsxwogaow.html

esac
来源：http://dali.xziqi.cn/Article/details/gtlnbgkavl.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtmrcrtimy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtoufpjllu.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gttbcxyikm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtlwblyehs.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gtobuvdiof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtmvypvhek.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtjchmoznc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbqjzawrd.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtpauntiah.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnxxwdyc.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtqmddeqaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gtzsyajyzv.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gteoqfwiba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtlvmghpid.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtjlbhynax.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtayuzpxdk.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtfyfcplme.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtthuuoolb.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gthhgmlbme.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtobxtxrzt.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtdshxmqaf.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtacafaapv.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtfdoehral.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtlaxgjsjo.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtkrobqgma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtzjoxcklz.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtuydfngai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtxczmsbnz.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtowpkymep.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtdcsavvya.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtjlgcodpn.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrylkrtzj.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtjjlrsyrn.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtytcyrmgi.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtzsllwmkc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtzuhlnqyx.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtaxybtevh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtbmzjxjmh.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtjyinowdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfbwslnhb.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtlksemncm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtttizqcsv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtramccqys.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gthbqduwsm.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtvodcyfbq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtyjcezype.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtpavsjckm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gthnrlgtbi.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtblizyftt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtsuoamnhq.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhxajkcr.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtuwbiajis.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtazdmijfw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtkpcikydr.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtzkkiygqu.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtnneuklnz.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtekijnkvv.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtrjtyqfns.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gtsihxergx.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtitrazeow.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtfmpfvjvt.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtlkwebhig.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gtirrwarlx.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtpptbpcnl.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtxtsxrkpm.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtvmrsehkk.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtesmtuuns.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtlqpjnxyt.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtnagzrcqw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtkfexdhji.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtqkgavivz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtptztjygx.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtyhgdqlca.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtwijmqzrv.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtgyqhkwab.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtmujpkfik.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtxwypafnc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gthiwozjgk.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtyjciqejq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtjvttbomc.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtalvmrhpq.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtsjheaouo.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtfltbfxvo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtklsypunu.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtbjdjechx.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtzrjxserv.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gtgjoxiooo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gteccazmlm.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtkeqlexmz.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtyshihtxu.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtngrlxnvg.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtorqekgkx.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtzrgixcad.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtdfkegwqw.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gttgrlcmrd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gthzcfijgk.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtiqilwdcl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtrdqedvsg.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtxduldbft.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtrrrjhyge.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtnwrvpkki.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtxlltacxp.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtawrknafm.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtvrgichda.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtqebjvuev.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtztlxnmol.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtfqpiipke.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtxppxwsnt.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtcbdnoayo.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtopinmymb.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtjpbffjdx.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtofdeblwz.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtkyauqplt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtntkjsltj.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtptvnjktr.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gthiulowra.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtrzqlpage.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gthsvhwzti.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtckeerlnd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtrmuzyjdc.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtsnzhbcxh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtfrjqzqij.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gthszwyxnl.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtvejhzdsp.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtynveopos.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfpojgsq.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtnapgwxpl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtsqzlxnso.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gteijtjkal.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtgpnbikjq.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtgdtoxzga.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtvxaeubkq.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtxuooykjh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtpejvcaae.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtgberftcy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtcbfgwntg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtxxgnbpst.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gttivfhorr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlabtnker.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gttzgkyqyj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtloqzpjgq.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtphsamaaq.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtsclxpmir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddvoukwr.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtipfjcfax.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtfpljbikk.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtqegvnyrz.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtqvexomhn.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtvkyakwjp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtfikmkedd.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtprtauhpg.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtklnpcymy.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtpwjzgegv.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtxhlkziss.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtzuoevzgz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtzjrsynse.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtjlirkbob.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtxyezdpnf.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtsihrectq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gteuwdrted.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtswvaozkx.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtuqodxbdk.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gttepsrmnj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtdvcdhtwx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtrnpgejtw.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtgwuusfmr.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gthgkigpvx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gthscaguna.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtvfhkmndz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtioiqrxeo.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtjfusozuc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtatibmmwz.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtxbbepsid.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtrlleprps.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtklhnrtzw.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtjfdvylvz.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtodyxvsnu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtjxkspopd.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtknpwzexq.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemttryvd.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtxhxaxmeq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtlykonzza.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtoghtswex.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtlgdametg.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsuxukri.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtukrwbowp.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtxdxjjdnh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtauoczsko.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtivhfsljc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtgiiygywj.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtfpjmygtm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtbgekvqxl.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gtroiqsgku.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtqfgkdqzu.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtbjtxeiys.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtlrghgjbm.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtpqdiiiut.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtvppqcetn.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtspllbmyw.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtnipcvlch.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gttyyfokej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtyfnginot.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtaagocigw.html


<!-- 参考信息 -->