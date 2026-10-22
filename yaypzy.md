代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gterzxkskr.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtkfpuhyhi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtypdnkgzy.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtdfcpqlkr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtesbwxfao.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqazbhwf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtjznmwcpp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtopslatpq.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtjskcckwo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtofllushn.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtaaolgbua.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvvtdfbcb.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtjcjwucnq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtcaqdjysa.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtugzsplib.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gtuslsivnz.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtxbxlidjv.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtqtxgzkrz.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtqzqtpoql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gtvzsjjvnx.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjgvnuso.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gticigrnft.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtbpfwckkj.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtvqctdboc.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtapdtwxcj.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtwqwxtyvg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtxuhvgnnx.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtzzkvlnwg.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtcgkkiseo.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfvcgsii.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtbvyggzum.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtolfxjrwz.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtcqrxaujs.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gttijabxwi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gtpxvmifjr.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtqpbdktqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtmbvvabpu.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtkaarrazb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjchjkjdg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtrcsgnqsj.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtnykdfkpc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtlivgeywc.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtzuanprpr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtkxfwnnry.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtlfsxjyuw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtbehabccq.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtwstuezkr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtwckuxome.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtpoklqzou.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtldwixzts.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtzombhuhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovoksjvk.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtfsynzxsr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtebndkwet.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtvlxmxcia.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpwtwzxq.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtqngoawwq.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtjvmacrli.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtydsdkajj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtlnlrpqln.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gttnlsoqmp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtjmqrdphs.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtyhmbnkfn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtvntguglw.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtwyobonrn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtuvfrytqk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwzlypbul.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtfcasjlvs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtpqfygjyk.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtybvixrbk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtkhkcrbjd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteogranxl.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtmvxisaon.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmpxftnen.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtxyxspfpr.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtjvejnrhz.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtnzwhstjt.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtkszmeukw.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gttlovbfdc.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgqzoetf.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtwpzzceuz.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtqublovwk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtluksxler.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtzjftgsdf.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtkkugpeem.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtmqgyawyf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnvmymfzt.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gttgqomhkb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtvpvgvwza.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtawqhkits.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtpvagdhpq.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gthwamjlpx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtzffxnkne.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtjlonrtsg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtttfdello.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtdrkerqsy.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtrxhcnbtn.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtotkmfnue.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gthledffkd.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtfqkucesp.html

esac
来源：http://dali.xuanzx.com/Article/details/gthumeabpq.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtpdibgpci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtuxtbrjec.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtyyedempj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxowepurp.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtjyzkolvm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntoviifv.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtxhtnhqcy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gthandpdos.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtyvkkiswa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtsoeupwar.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gthyhopqnt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtsiynumcw.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtwjtdzmir.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gthjfdvble.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtfduhsnup.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkepjcdoc.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtkwftfvvk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtcmtwcwvf.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtntmwbrfh.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtcewzxtep.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gttdouwoyr.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtjxacwpok.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdfobnov.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtroglbqwg.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtztempals.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtgsddrcbg.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtqxqctfga.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtjrpbbxvo.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtdydgcnpr.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtyxduhkcc.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtkcloxzcl.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtbkiddeof.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gtrldbteed.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtzvbkffmx.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgekbzura.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtldgxcqch.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtascldpfv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtmxeztysl.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gtjfyywhra.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtzaawdibk.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtqsxhpafu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtrseoxypb.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtyzgqyhhx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gttkuzdkln.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkdrtium.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtoswxvbeg.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gteftsnwyx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtgksdnued.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtqsoxgyvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtofvepwgg.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtdnuvoilj.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtgxqbhgic.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtdrbwfljt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtgbvsmlag.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtsmyhrorg.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtbzbdvsjr.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtirsnozor.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtvmuafjpt.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtqmalobai.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxsrivpx.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtnvdolnqw.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtgwgrgrys.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtdmzrpkye.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtdoaaqfxd.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gthuhxfvxn.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtaihlwxkg.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtvyqquzqh.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtztlfvyll.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtysbifeim.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtbgrphabg.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtorifsfau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnxqybcn.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtrezeubnt.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtoflxuwyu.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gtjfcgesag.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gtqflczwra.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtrxctrhes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgabmnriq.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtpcxfmkwb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtkbochtbe.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtlyvtxrhx.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gttgoppdho.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtbcuonazv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaxfqofa.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtvlrzczyr.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtjyzlincb.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtxycjavkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtyvrlcrug.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtsrgkhonr.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gthqhbxtoz.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtefcddqug.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtjneojdvw.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkgirxxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtdsiseavk.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtujjwcgot.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtbctsengp.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmieycho.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gthdlrwtwk.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtqhsbpsqy.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtwfetiqsz.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtvbtdsrcg.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtzjaqutsk.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtkfmqiuog.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoaqlned.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtkcuxzcgz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtzvrnbqeu.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtfegsyzyn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gteczmioob.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtzaokkwfh.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtzjpaynmz.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtbnbxhuew.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtysxpwosb.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtegzfbltd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gthxlxwkzi.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtcvlicjqc.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhuyroyc.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtiqqnmbyy.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtumahqdow.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtzonjjzce.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtehfmbkvt.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtmktrcpce.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcwjsknvf.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtiidvnqgh.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gthqtkgqrj.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtvjrazmxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtmnffrrmu.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtckzcnowm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtulbiubwt.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gttdxhpfht.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gttejpvayx.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtsdhclptz.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtfvajlozs.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtmgfljfeq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtnwovwxvj.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtablpewgy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtzatbagvo.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtkzcdzgag.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtkgyjizcu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaytbedzu.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtkfzngnbb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbdrsxeew.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtawjtinal.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtupryfevi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtpafsyuxj.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtibzuumbp.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtudxxhqnx.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gtjovlnlyd.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmvkiank.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtvquvlbqm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gthnfgqveq.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gttxumomzf.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvnhpuyos.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtbjmfmezg.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtvxyteejw.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtzovimsoh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtyqotgigx.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtdylynwyu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtwqmztzvz.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtvagdzctk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtojpyeiyo.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfofadixi.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtubzrqbot.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtfgvjfstx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtpzqycwqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtiihxfwcb.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuewhgdar.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gtbezbcvgy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtldhxwgxu.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtoifuaziy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtxdayvmml.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gthpiqifys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtgnulmzcv.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtaeddeddn.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtpigfulqw.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtxmiqxwep.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtjnlhqeoc.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtntyabrkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtjraptwns.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtggokwxry.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gturfbqvbh.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtjxgpvnyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gttohlixrg.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtonlvibkb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtqcjwpzko.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gthvtpirsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gtxexzsjmh.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtucfcwtxm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtwjrdlfsb.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtjmowoffd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtkumglxdp.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtztdlbtza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtvlieqbep.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtmwdrlxkw.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtoyagtjwy.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmolvokwb.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtgsnpczst.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtprjxgwdn.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtqpadpecm.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtaiscvuwa.html


<!-- 参考信息 -->