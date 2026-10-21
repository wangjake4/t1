代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtznwkcvbj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtnyslvzvt.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtqjrhnzae.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gteuqlluya.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtwrhdszbo.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtxjxjudfe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtdyajrytm.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtyicwpcoa.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtubhzkszq.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtjsncffmh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfqsmebp.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtodawcpnx.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtctmndrso.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtnqtgfklo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtdqvirdtn.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtvdmqlwua.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gttonlnsgw.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtiivdlmrk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtkejekbax.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtgrjzjmfj.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtthkkfmwd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtlkiasygh.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtyplazkcy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtelkfkipc.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtqesmsaeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtbdhtuwmg.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtpokpeqfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtwvujzsgi.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjqzpwpu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtghgmnqrb.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtxkkcieal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtykahviea.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtrdufknpu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtttczqpyd.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtrmfnzduv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtszycueor.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtyuxnqosa.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtnjtfqwyb.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtmvqysmuk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtcgxdxbjn.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkmjvukr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gthhdbwsjk.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtcoxixwrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtxgcwroug.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtouhmwjmw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtadkiezrt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvbgtaame.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtdjcemttw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtceqaancv.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtcnbsalmw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtfuwpxlcq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtaxaxugor.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtutfhlnvp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnkzpidks.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtyiaukmvs.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtwfzbqprt.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtknsmbsht.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtjupvpoue.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtzizcxbxf.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtknwydmii.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtpjogpcgb.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdewbqahn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gtfucdgwmw.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtlzsjnhht.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gtosyolkff.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtxugcyyhe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtjuawbuqq.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtnotnqmfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtpsidaaxc.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtdgtpsmfh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gttznmhwbw.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtnxqimrzo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtkkmcbxzw.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtbjnucbvp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtyaclgyca.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtrxvhilcd.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtrukaebxv.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtnhqakuej.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtsigvdwar.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtjgoitefa.html

esac
来源：http://dali.zdqjudy.top/Article/details/gthvzlbque.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtbjoqjskv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtlbjnieky.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtxtuezaqb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtjmpffkkx.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnumguzsx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtowdqfssn.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtbeeoqeik.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtelshfqpr.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtrbvyemoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtoczlbtto.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtkykugtew.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtxymwobfn.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtmvvgubdh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtkedcfffx.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtyanjizzq.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtyhttkjrb.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtphrnvkps.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtqrqikcns.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtuzdwktxj.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqidrisw.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeiexkww.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtosbnnfnp.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtyvacftco.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtybcgabgx.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtgbanwbfn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtggqdnryi.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtbobojwub.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtggvmghsv.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszghhggc.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtlbgwsqwp.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtgqjijwzg.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gthhqcrbnc.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtvgsazpkb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtyuzvalin.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtmrvkqgug.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtzztubyxu.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcgkylex.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtqwnnntpt.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtymyjvcte.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtldrrvlhh.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtpflqqfie.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtwsavmety.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtklowhplq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtlzekcnla.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtptwkuxob.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtmdndjlry.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtqjwctkpw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtulxehcsn.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gthnhaxnyi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtkzxpqpjf.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtkytlamyv.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqncyqifp.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtdrarhjth.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtdzdcvozs.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtqyvjpevp.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfwwcsst.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtregluaxm.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtftyjljbu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtyjvzpruw.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtvgrygueq.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtezsshxyi.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtujoerkow.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtaclykisz.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtngtstmpg.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gthxduioln.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtobqqftnd.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtcgcmvcye.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtquhpffzf.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gteiksxdgo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtbwauhjqt.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtceezdysr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtfhexmhns.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtycbvwiqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gthtfhkgtr.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtpuunhlzm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gteyuxkhwn.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gtwyabeomz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gttarunerx.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtuondjjjr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtgihptpbw.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtajdxzvbc.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtnkwicnqz.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtzmdpgjwt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtlvytwqln.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gttlnxxwml.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtmqgfntzn.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtbsnxjofe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gttqbyvqgd.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtnihiuufy.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtvzwwqyoy.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gtpbnvysso.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtoylchsfx.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtgdwduvhc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtacomlwdh.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtlexbrrbv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtuxhrqvzv.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gteeflgtpx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtchuamovp.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtzoibqdjz.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtzdcerbro.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtzhbyjklm.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtlumypkfl.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtltgyulnp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtpstirduz.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdxskvix.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtqvkqfoko.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtcekdrypz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtmzfnxkfp.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtqumnzuqy.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gthmbhqknm.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtmoytrlcj.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtutkcncbc.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtxizjkeuz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtlsonkpbs.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtwprxmdll.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtyjzgtwbl.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtalajuzhv.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtbnkhpgts.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtzkgiskpi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtgxeenwba.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gterhojnif.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtvbjdxork.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtgwkybnok.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtsljzqzgo.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtyysnapvm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gthyczuuat.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbhxfuvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtobgzewdd.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gthadggzlq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtuvwcvtvt.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtuklcehmx.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtgkpwymhb.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtmidvhztz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtlpoccmky.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtplrnpaag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtlzvayubp.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtzsmurzmc.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtkanuckay.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvbirugcp.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtqisznyow.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcbobqswq.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtugitoggh.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtlhwbswfn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtwpwhwnuz.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtjukncxbh.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtlkdezwmv.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtgskdlyfi.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtmbdxhhgs.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtmoioiwxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtmkkvssdc.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtcnuuqbnl.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtvwqbjijh.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtxlavjsci.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtnuxnpdbl.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtiltuvecs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtmmxzzksc.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtpmrrulgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtrurnyead.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtgbgtjlby.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gttiimdttw.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtvalioeyn.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtfbpnjdsz.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtihajssue.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtrwyeafaa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtjpynoluq.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtbxjhbjmy.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtllbuwitk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gthewszkig.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtpdsuspbp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtfufailkj.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtwfkpvgbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtcuyktafy.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtmnscjvov.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtvvjkidca.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtizfsmgaj.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtxfobrmtt.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtxgnxap.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtjhkmaouw.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtuyzlwiql.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspattpxo.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtbbpbucog.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtwcajevoe.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtmengxnrw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtkdydxkqf.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtlgvcggtd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtzoepgqhj.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtkzorrznt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtuomuzoum.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwsxcbao.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtxlwxefkz.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtsxpxhwuj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtqksdkgie.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtvhtzwmyh.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtdrflviqq.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtyfsqnosa.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtgkxpxqls.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtkrlzrxyv.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtsnlqzypp.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkxpptpzk.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtcmuwtdoa.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gthtgmiosm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtsdzxemou.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtdodbojur.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtslbanxmf.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gthxdrffnx.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtiylvdwej.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtwwgmcidr.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtcobpfbtn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtiplmomgz.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtcnjnjclr.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtdsgelxxm.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtsdzculak.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtxtcgzpki.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtjkhjqglp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtmnnrnzpb.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtcykegqxo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtzdtrnnjs.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gtjxdldupw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtjmmzjado.html


<!-- 参考信息 -->