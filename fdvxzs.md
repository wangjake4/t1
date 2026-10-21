代发 wailian999

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtpytwlvqd.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtkxmobcre.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtiplpldwv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtlfrpqbky.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtzwxfpzog.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtbpepsayh.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtygvxqwze.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gthzkgvdsg.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtpxrfwbdf.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gthcxzefar.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtkbceipve.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gteinpnhda.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtmzujeric.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtvqfahgkv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtcmgcgmru.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gthlkwzcku.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkgwfgris.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtlainihpu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtarnhoxkn.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtquteetpq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gtlhvhrowz.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtkdnjrwaj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtbtefxvua.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtgkblpwce.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxzcdetp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtmyeetivf.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtywbcyrre.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwnxuoay.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtcutysidg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtxprecilb.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtesoxsxfe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtgabpvive.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtyjedgfra.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthuvjhxfs.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtlswjyhvd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthqzjkaye.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtlrmovsui.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfinpdcam.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtqekzyrnn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjnjkxbjp.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtvqpddyxv.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtemmnaoqq.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtlqnygals.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtdlhacqwx.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtqyngulnr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtabdaqojg.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtoovnwybj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtpkqzbqjb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gtgclvlimb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtmmkfaefd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gthjxpbmcf.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtfnhfexal.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtfvfstwmh.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwpolwku.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gttqstrsvp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtueyvygjy.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtrecjlxkh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqftsqngk.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtqxsmmihb.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtkdqqoxge.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtrrmvgusu.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtcejszaft.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtieeqhffq.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtpmjuwtsb.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtkrstdfgh.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gthbitvzcb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtjvsylfkv.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtbjyidtoo.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtuwhpryuw.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtfblksasg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtjfktagro.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtnlmvswxl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtlatljaec.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtukmbycba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gteugynodd.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtdjkuemlk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtjqaddwut.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtmjdqkblh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtbtuftqrg.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gtkuzezetl.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtkuqjawck.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtndzootrb.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtogilppmz.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtdxnbagcv.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtudvrfhwk.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gtpcgeweai.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtkspiuwif.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtjzjcqroq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtxqvsfxrb.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtxtdjimvy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtmuifouqx.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtgwldubij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtrlfqaowf.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtiubvnewn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtxiqfxvzs.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtmaeauccv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtvinxuxrv.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtlkzcomsb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtzcnfyeiq.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtuzfjgrzm.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtppzutuoe.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtoarsybkf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvjeaovcq.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirtrhuct.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrtskemt.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjvsnjma.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gthqrmpcoo.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtzospckbc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtyaolpjni.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtuuwurjmh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtynxfvcun.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtzxoylzay.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtdpoguupq.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtmgkgngzp.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gthdjphenn.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtouefdnqi.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtlfpwpmto.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbpitorj.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvmmbxtx.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtnrctujgo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtwqzuozca.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtthxassgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtmgcrxwtk.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gthyouushs.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtnlbructs.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtlgjiklji.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtkkufeyug.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtrjngutrw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtkefnfgct.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtyqfbcdoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtryeufqwg.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtvhisqtiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtdnnjmjgp.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gtwgeiqwgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtknboxshi.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gtkydgoleg.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtlbcnplwn.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtknpvattv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtodgsblnz.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtjexlbtav.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtsffgclxd.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtmndudptc.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtzxntihlt.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtzilipnwn.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmddhphbf.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtlqjojryl.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtyhbzpjsz.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtehkbpqae.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtsxnnoywb.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtyptflwzf.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtmukpokzs.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtdpkikuss.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtyvjoejmk.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gthytirtkv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtmubulejk.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtrynxsemc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtogqqunzt.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtbbyileaa.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtxqxqzfkr.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtctilgiua.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtctlnufvv.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gtlqbmhsha.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtggipxtfv.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtmmlkyadn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtqyxqfgpx.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtqluxuhyh.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtswwuhouo.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtzgsrjffq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtzvmekvjc.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtlrkhbwpm.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gteeyfapqw.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gttmfsbbrv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtahvcwdkf.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtqgqsfjlx.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtiijaqmhh.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gthdbskqfz.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtrnewxjor.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gtspltncna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtiuxseibh.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtyvdouosw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtiliztrjs.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtmrewsbxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gttqnidsgu.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtzdlvonce.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtqicqrwmp.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtofzymivt.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtrhihsfso.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gthabnnljj.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtefpmlfco.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtzmrvoohm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtrydaijuo.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtajtbkdvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtdkgqojln.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtxdaibmwn.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtitubuzna.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtzargfbvi.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtercuvizs.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtwbidsiea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtdujivzab.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtzxboysta.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtftjwajnt.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gttrcbnvdk.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahjcipdp.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtsotibjue.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtqzmphtba.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtkdrfgvau.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtowsprnwm.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtbtdolhmu.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtthtwkpmi.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtpfdgmlff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtszxclhiu.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtytmbxbjw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtclfcnysg.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gttudfbaav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtlawqovis.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtybnimzrr.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtwejoqnxn.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtjsxawejm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvribwqwi.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtgbicfzpt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtcmxlvdee.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtokctfrbx.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvezbcjr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtptjhpctm.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtgusjyrkm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthryflexm.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlqrlsvzk.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtrqjuejox.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtyutpksex.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtrcvucixe.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtexhtpbuz.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtayoeizez.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtjxcdbenl.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtqiewrxbv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtjqbasrup.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtggqkqyhg.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjpxnbnz.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtdmizlwec.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gthfowscls.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtrgwmqpwu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtcwjkzbkf.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtjvykqgsv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtsrnngglr.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtuefgaazt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gthzxcaptf.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtmpwjhufo.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtgzvrjhax.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtexmscykj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtxbdhjzmf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtksdzshnt.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmfyxcvw.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtgautpicf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtwedxkxau.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtdibhzhel.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtdpgtjxod.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtyfgenknl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtemdezcqz.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtasbvjgbi.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtyvrzkjpi.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwgzbrbz.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtvxukqcux.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdshkwtl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtrqqhajeg.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtoiqnotvo.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtmlqbvoop.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gthdzhddcb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtypzjdcni.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtqsdnteee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtbpgiglsq.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtyeovbpwa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzotpykca.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gthigmgimo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtijtfhmrr.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtqvvflnbe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtkdbjrorm.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtupwmzxbk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubjchazt.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtyddcismt.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtddxewhfa.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtkxcqbnht.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtboaructi.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtnqzqxapf.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgdmavlh.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtcbsqwfov.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtellocdsp.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gthtleivwe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtllhjutyx.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpiaebqe.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtyehccyvt.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtckcqzuvk.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtsoygxogg.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfzaunjgk.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtbsaizkmx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gteffdosls.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjjbcutft.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtyvklsekp.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtlqamyjsn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtzndkepra.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gthqisttlv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtksiwxhhw.html


<!-- 参考信息 -->