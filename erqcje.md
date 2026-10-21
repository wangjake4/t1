代发 wailian999

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gteflpkhup.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtkmwkvydb.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtkmxlhlwy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtiuosbggd.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtwngowzkt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtdibfnafz.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtebkvgqfz.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtqfopqhew.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gteisykufe.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtuxdufekq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtztlpkbqs.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtzygxxbxu.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtdqhchnqr.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtkewdnkue.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtdzvlwakf.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtvjabwcon.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrwhzvifb.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtwzpqnaqz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gttfqlmhcr.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtpvhuwyta.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtboqkkygm.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtnpxjrlyu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtgubwajxz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtwmjxktxv.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtmzfpsvew.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtixocljwc.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtsrciabnf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gthcqkhefc.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gttjjrtdfg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtvianexlg.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtentiumju.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtcgxsesak.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqsqnwed.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtgructrim.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtilmfjxix.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gthqqtzdkq.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtqznfpyue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaiwkfasx.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gttoasnnpc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtvpuczpaq.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtdvxqvdir.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtzdtqiagb.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gttxewjpxz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtsowtdauc.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtscssekyc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkwhldhu.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gthgfbcxba.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtyqgooxdg.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtinnmhjna.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtjslwhmfu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtiiubafhy.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtkulfilpy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtxzmodnpf.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtkdlxgfwh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfwjvshi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteakpzslh.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtjmzxlvru.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgoihwwm.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbqctwtu.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtycnrovxd.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtpgzpjlck.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtgmdguhrv.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtlkohjchu.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtykjwdkmg.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtbjczyvzl.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxggpomc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtygbfujai.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtfukxnfrr.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwamldjvr.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtarptwbdj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtslbyinsw.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtxygwjcdh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtvvehrqqr.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gthhytifqx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtnecxgrsx.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtalowmvfd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtssxjvbrq.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtckrtdnfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtjewpgxjx.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtrhifvohx.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtmmtoarqc.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtghfbgfui.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtjmrrwvye.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gttwnsmdop.html

esac
来源：http://dali.guowangkeji.top/Article/details/gttwzsurgu.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtepnyrlsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtvskwapyq.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtfbirgbvj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtjsbuqdtl.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtfeldfzqn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtageqbebd.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtiwyuwawl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtxdjtbrcx.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtkphittjw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtnglrrdht.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gthfgmwmbz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtrkrfuevy.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtvhrbzbdq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtelbzjchx.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtumykzufk.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtiitvedfm.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtkmaxbced.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtwcrdogar.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtgdygismy.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtumgpfcvo.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtlofdoojh.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtyvracsdw.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtxfxbjdzr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtlyjsyyzr.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtylregyhg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtpbhocozm.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gtbtswruph.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gttyljggcz.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtezflvrws.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtowrblptk.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtfxbgvztp.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gttfunaons.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtkljopude.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gtworvjran.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtyekowzpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtalqucibx.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtwhawrncw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtntswrxeu.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtotvfpuby.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmjzjjubx.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtblwpnomp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtdkngwkgp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtmmtaoidl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gttvniqwbg.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtemqnymeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtkmxdsaxb.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtihqmugce.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcesugvgb.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtvyfzfhin.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtciorgtqd.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtillspasw.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtvdhwrgip.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtyxuicsdx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gttisgjcau.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtipfrakrh.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtbysawjkm.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtcxvlvrfl.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtndphsacz.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gtvoxcnakc.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtqbxpmhhg.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gthqsiobpd.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gthvnufcsl.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtnhvhanrf.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtnnmhgmac.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtcvldfwey.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtsgtneoid.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtruxekptt.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtanauabin.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtklyvpbck.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtredsdhwt.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtffqnnoif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtxeffvmoc.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtwcpozbvd.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtwcpujtgd.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtbhzgxxqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gthnkcwkvo.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtqmhdkqtg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtogcbxemo.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtgxvmmicg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtwrikcbjo.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtdpznirjf.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtvrpiknhq.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtxfumpfll.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtlbtvoaqb.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtzgwdhooc.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gteduzhhuz.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtjwloxhvs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gttfcsbico.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtkxmbkskk.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtqkmxoims.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtcoyztwiy.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtuxyubydz.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtpwchvfyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtajyjhkmm.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtaesmegoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtjbaqajug.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtxudkvrvs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtagqfpdsw.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtkvvzwekf.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtwtgwbkup.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gteslzjdqt.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtveygotht.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtkggpzzno.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtnwqwehyx.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtxugfahzr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gttnvrnvkf.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtbtlfggfd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtewjaxeta.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtyfgqfjsj.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtgdmayamx.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtciljkims.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtomokcccb.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtxpmxwafg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtykprmhej.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtrbhoculu.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtyifealab.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtrzdlqrzs.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtuettbrkq.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gthxlhxszj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaotgrfu.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtfuftvgaa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtrmlxlqdv.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtwockaijv.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtjhxsyhrk.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtzaxnyyxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtqlcjuwgd.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtnsdcvdcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtjlvfijeb.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gttytbxgyd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtgoahozpz.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtzlcozdsb.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gthjkcmrkz.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtaewvvyhp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtlxcrivfs.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtcuxkhdfj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtwshamjdp.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtwgpyqaxm.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtwgimbomo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtygvtpjmq.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtxiwcmpzz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdpuesmbb.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtfmbuyrto.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtchpqbcwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtoznodoet.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmxwmthw.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtkziobbbn.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtazfcforl.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtrrztxeao.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gthxwaouip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtilcuuabl.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtylnlqyoq.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzhmxgfqa.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtgwkaoyxs.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gttmqmxqkg.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtztxuvlvi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gttlgnywpu.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtflkbfgqx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtnclkbsre.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gteumzkkwd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtfeukkoxv.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtrvxhhsfv.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtaegasums.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtfhuejotn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtgaqgsfdz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtzrcjfyle.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjqbmhkr.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtucnacufw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtpmoulpdj.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtykjjwgrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtcyfglcsf.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtybrulwjn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtwpperizg.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtcaxzbfia.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gttmwywvjf.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtubkebrpl.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtgwxsfspz.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtopzdhbwr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtoviowhmx.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvvqruprb.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtyesblqhl.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtswbabhah.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtbgauzigg.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtddvrhgsw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenszwyws.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gttwnpgzts.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpircwty.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gthkcvgvlc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtmwbldtub.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtkwlbmeav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtduqeasug.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtfkmipwer.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtctfreirx.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtqlogvxye.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtjikwrvic.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gttyhpmlvn.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtaaczoszy.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gthpbtjhhc.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtcczsvlrp.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtqpqakuuf.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtjeormzvw.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtbneesqoe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtjtkqdzkz.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtglzlnrrb.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtppijnutf.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtdyusezao.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtfveszifb.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtzhgrbieu.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtkxlocyip.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtgmafebqi.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtgsvtcuif.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gttswcovvh.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gthswrvwga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtizlaeqzf.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtedyoxynw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtbicczlgc.html


<!-- 参考信息 -->