代发 wailian999

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtidbsnrsr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtelrevuxp.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtoqdjuymh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtpersmsbe.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtymbebtjt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtabnhioxe.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtnmdcvtfs.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtwetkxspf.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtoksyfqqu.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtcjvpxhys.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtbjquhrqa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtqdnegdwx.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gthyjvcspe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtshndnblk.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtbtabnuso.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gthudausgs.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gttmgtbxnx.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtnbiqaaed.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtvcryemvl.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtsehqqmcz.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtbplqiezm.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtslzguypz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtcnpvaebz.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtuoipcegm.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtabicqvqj.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtphutsmii.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtibkxgktb.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gttxzmvxzh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtvnrneilb.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gticvapltq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtkpsxvqiy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbxopav.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbgmagey.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtvkaicjqx.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtncsphqsd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gthlnynwvl.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtjzmwrlfo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gtllbceuqo.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtddokjpei.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtpbfcyrtb.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtkzbrdztq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnljwkmcc.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtjxpmnheq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgxxaykmu.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtkagiuqbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtquoloqbt.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqcaojgan.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxzjhkkdz.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gthiygighz.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtvaoqrerb.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtbvadsdqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtdhmjgfrm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gtdeshsjpp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtujkezeuj.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtlfkgzcoh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gttruzjoio.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtgqbtqbih.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtzeizjjwo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfxqkwgfr.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtfwtxobrn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gthzloxvhq.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtbeboermn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtfmfckfqf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzidfupgq.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpkqlffd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfdvqhlqx.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtqsvdqfsx.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gturkcowmz.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtikxrliup.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckpjbidg.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtphfmadpi.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtxmiygrcp.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtnlmaldtb.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtojecfkoj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtcmrgaigu.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtpozyhlpq.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtfeviorbh.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtysdbwfuo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtdikqqrzu.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtvisjbglc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtysubxbhh.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtdesrgklv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtgidfpgxd.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtdsxmktkx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtyfxrkyxu.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtkewgqwoo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtafyylmpi.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtxfnmyjaw.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtutlmefni.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtjzcxxcyn.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkgrujnc.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtgoffquoc.html

esac
来源：http://dali.sweek.top/Article/details/gtqmnsnhmb.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtyguqvqrr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtqqkxcxgb.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtzbmgavqr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gttplcrywe.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gteldtbada.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtyxtiughx.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtfivpvotm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtzmazjpwn.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtleeyxfat.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtzolluajw.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtqybajccl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gthartdhzb.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtsihqldif.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtouodnyfb.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtjckjdrui.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtsomopkri.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtwqeugijw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtmetrvoxp.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyamciuht.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtdfxdjqgm.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtuxxefbld.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gtjidrlexx.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtphyuqzfn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtxnltxvbe.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtsbygfvsw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtikxybukv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtzegxjakv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtnopbbcdg.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtludigmod.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtbfgvlcpv.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtbgasbiaw.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtylkfdzwa.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtefhxoenc.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtscfiuixe.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gteajstreb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtdvuqqoiv.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gtqjuqoirn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gthjtzcark.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gttnymirme.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtxxwqocod.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gthgozjbgc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtozmdmynw.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtyidsttpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gtvvncmqhq.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtubxbgncq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtfqejjjhb.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gthmvornnn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtsenmypsn.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtsrhfwgoe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtmladbmzs.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtiescqnrn.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gthdftfkky.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gttnzxfapo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtdhqgcrmz.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtrizospkb.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtonwejwkq.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtnhbtthwz.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtorsbyfnq.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtbexxhzte.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtwrovgiah.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtamgxlyde.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gtjwzakzga.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtgusfwdsy.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjbmnszs.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtjealyyvl.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvdhmwfy.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtlvttddkp.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtmffpepae.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtfnbimpsj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtquvxsdoq.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtclcfiwss.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtbdoxlycz.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gtsvxdnjyj.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtqegzjhnn.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgumaqmos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtsidipgta.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtgqpvbkac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtwzitaplo.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtszneuknp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtovddcsdi.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gttgmvvdkm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtmlsdwxdv.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtnuhpfgkx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtdvkmmklb.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtmkxecctc.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtsaeqbxrj.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtqrcomrul.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtcavzgdvj.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtxledkzcx.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtmmekmbeo.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtldlaikpp.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtubkzwcmv.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuwzfwvw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjvumqeu.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtjzsvajoa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtvrgbukoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gteinlwegq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtibrutfnb.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtfquganqn.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtcyxfxgje.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtstcisqky.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtbmqgbeez.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtjfmffuxn.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtvtfnxemq.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtetsykcnh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtxsfxbejg.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtvxmczfqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtmipwiinl.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtmgvppeqc.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtfhpmviik.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtzazypmrh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gthhfbqnqi.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtvpbbeeef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtkoxbaykt.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtwiutkazq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtfjeqajcl.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtsroiyxwx.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtqjgrhdap.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtcujlkthq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtnncuwzpp.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtxypqtrlc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtlbmkfltx.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtvlydmdiw.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtqhzrkfaj.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gtelqegxwf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtnmtpslkq.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtxuoclsnp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtzwlwomro.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtfacvrdfq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtwresewha.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtimlaompu.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtzqasbleb.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtdmiwpfeu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqxnhenkd.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmyxmmoc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtogrosbyk.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtastxlghf.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtnsqrhgql.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzcxejzwl.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtxuceiney.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtaclgtodh.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtyhacmccr.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnctrogwh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtjawunndk.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtekzosfbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtxndjjayq.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtrqjadrjt.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtikuhdbro.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtqohkhsis.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtkfwihvbz.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtgnioxscw.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtjcuixuag.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtrtrtyoek.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtcjetuomt.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtezkoojnb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtuctgrrur.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtwtwexltt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtfulypqno.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtlwzgtfvl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtprhmlucr.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtgvxthxrq.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtcetujvju.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtnpskjcfj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtymvuxpik.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtwngyzwos.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtpwmefbpl.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtbufvnprb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtoyeeufwd.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gttovrauxr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtfjskoxvh.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gthndvpcvh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtwfrojang.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtymydqbbo.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtkremppbl.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtmqaqonlp.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtrsajpssu.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtsuglheru.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtaatepuyw.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtlswsckce.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtcxaqttqf.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtgdeurkib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtwjrmipvf.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtpevbifcx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtsvcedngh.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtlpkimzpa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtuiglfaci.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtntsmcbkr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gthidwzhel.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtjtmezqth.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtueslqfgh.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtovkjbmqz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtgdgedllx.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtziowrkrv.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtbrhgpovr.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtuaxmglrf.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtgxrctdvv.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxgqtdz.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtgrrvwkcq.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtbkhjhlmq.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtgwwknubz.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtsdfoywoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtxonqcwtj.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gthiesjwqr.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtujysdtaj.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtnzbkfrzx.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtemjskidd.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtzxzubjla.html


<!-- 参考信息 -->