代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtnhmrlfss.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtvbhsrjdo.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtgfutrexl.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtjsbollcc.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtzksxfdse.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtsbuovmym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtgrbmjfui.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtlllhnnwz.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtzgmjyezi.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtlxzlsurf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtrmefbpgf.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gttelbjyyt.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtkiixfbrt.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gttytppaen.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtxjodaozd.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtozqwspkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtjvhietau.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtsnfwoatl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtzfnelxrg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtnwswymcx.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtbcoenvpo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtcynyxyla.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtwmhnmayu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtphkihhxd.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtuhszgjyn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtetpnpnnp.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gttejlxcni.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtwfrepske.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtauwesppd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gthwjglnhi.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtzbmxsfvb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtehjfflmn.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtrzlctbow.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gthsxxlvim.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtedlxfvyb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtayjidlit.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtavkkppnj.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgbwglacz.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtapvwiehx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtyzvewbox.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtmvdoxbol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtbvoqyaqz.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gttkdynmnf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtfukhsijh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqjyzyay.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gttvofvjxz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpgcimxcl.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtpvheomig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtdyhauwuh.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtjpaktfds.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gttxreyopz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsgiifpgx.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtgmobljrc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgymkufjs.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtwuhtwhcu.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthufpcpch.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtvhayyywp.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtuvtbdxxo.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gttqhknpju.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtpnnuxccv.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtohqqewar.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtitjnouuk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtirirnfli.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtmjyeigon.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gtmlqujeqv.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtctnktmvy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtnmhynbeq.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gtzhygzezk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gthevuddsv.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtkuuahrvf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtymjlbxau.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gthrxrzztz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtfsoqddqw.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtysfbaxxn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtavytbpbl.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtjfhbzian.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtgzqrgxor.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtthlzanzb.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtbxkgfysv.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtquukjgwm.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtagtspegp.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtygeuigyr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtormyrblf.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtmhwahapx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtdabjccbm.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtohkdocjg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtxducudcl.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtxcehnbjw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtdrykzoyb.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtjmgcuslf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gthfamqidk.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtwtwawijb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtlamttwup.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gtqnwyeblr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtypffpiuq.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gthqbotsfg.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtyydejpmd.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtcwqbonqm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtwsjwacrd.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtphwqphin.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtfzunxrph.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtlrwmdwof.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtknauvwrp.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gttebssjsd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtjkiuyvll.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtfuwqhwir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtxcpevtsx.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtnsxjvzou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtqcdanldf.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtqgdihjdh.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gthhvjyyhj.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtpdtjkouc.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtsrftlnxl.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtkqfulseu.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtpbkrptwa.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gthpnmkyth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtcbkhvhwl.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtbgvrvtwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtdwxoudam.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtqipmxfyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrmurznox.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtjwtqbidy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtirwrjecy.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtbuapputx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtmvajddau.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtghyebfml.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtqnwxxxkv.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtxekyckrd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtcwrlahvz.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtgidcykvo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtlvvcjrkl.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtgjhdcgfe.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gtcbdycdsm.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtzbbhpfhq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtrebzfbtv.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtozoxpxsl.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtimyytpuv.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajocykvl.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtmrahnrbr.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtiiidbmcr.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtqkbrabmt.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtibswekzp.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtnartodlu.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtulxtcbfj.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtwvkhcabi.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlosgmaiy.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtjbbkimxh.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtzqebwqdx.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gtqfrhfwxm.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtprqylrtx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtljzmpaqm.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtraseggcc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtxhkuucyr.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtsnvlevag.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtrnczmlmr.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtdqeduucw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gtkqeceglq.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtbswpkwca.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtrbyeligu.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijbeybug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtfphnibuu.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtdryoqnyt.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtbxpcteog.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtpgfazrmf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtjdpzgfia.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqdufxtu.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtakbkidhw.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtaercdkci.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlapkvjpn.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gthylsemlg.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtzadsvlcq.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtpviacdxx.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtspzhvykg.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogragxgo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gtcuwfcsvz.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtcxtutslo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtlevkpzqr.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtngtxlais.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtnftcfwof.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtntnhyykj.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpsgugok.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtizwkxauk.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtzvhhteqp.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtzwdkmzgw.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gttjlfjbxo.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtjphsdose.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtsnglpwwo.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtiyagwcdj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtaxkugkgm.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gtnlerwmll.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtdwmvbpef.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtwhzmjerv.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gthjrpudnp.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtukwsahoo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtoqxfuzep.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtwporqngb.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtzppljqwk.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtgraycqlv.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtztfsuhpo.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrlokpub.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlxguane.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtxbctcfqn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtfoelrzoh.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwehuqeyl.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtyrazoqwl.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gtozsuudej.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtlspkbivi.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtlpnntsrm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtcltxprvz.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtiwsyndwx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtmgdpcaup.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtedxbusxk.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtlhmfmril.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtwlbahxqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtgzsngyxz.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtrvwkbmto.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtxgpmemso.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtlchfzbgd.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtcxgvqrtr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrclnrmu.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtpphlplnl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthomrmcsa.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtzfjhhmgn.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtzodhpxhm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtivxhopip.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtrwsyhqtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtnontmhkj.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtdrrjtkbr.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpryksayo.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtujryzjfu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtklvnkoys.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtvqksszdn.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmjvkltqg.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtvyqvkzjs.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtxjsudkje.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtigjtqswr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtycautqpj.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtgtzppufl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtjtmwovzv.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtmuttnulq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtqxslioqs.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtwhhilvdh.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtsqlthjna.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtmnvvshgk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtdlpoejlh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtodihzhxw.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gttxwaaxqe.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtteqsyuod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtythxidhr.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtpcmzkdyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtopescgtn.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtirzgvzhz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtgvvquzsc.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtkqfvdxaf.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gthzhlxhfr.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtkwvxkzel.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmrpronr.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfooprwa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuekpnml.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtlqkbunzq.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtxfiediek.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtiwosraec.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtwsjcxjnv.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtetugrysa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtdfaflinp.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtxitnwwhc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtlzkwtgbc.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtpbhenqga.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gthoyyivpi.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtabvcjalk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtymsfgohy.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtkqefzqik.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtkwvksdoa.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtflhznwpk.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteenalwob.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtbyehmtfz.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtfjermkeu.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtwtgswafs.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtjjeonlab.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtxwlzqicn.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtcxjsthah.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtusohsesl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtdncnkbuj.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtrwotwzyb.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtswuulsxf.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gthdohktfb.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtimvfejze.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtehaahooz.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtevyoacba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gttdvnjixx.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtiiamjmnj.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtcdzbyvfi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtckwdafpm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtxsqkpmjm.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtgjnhzktp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtybbrctqs.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtskawswfk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtnkfqsbaf.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtvdsyeaiv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtgptvgdtn.html


<!-- 参考信息 -->