代发 wailian999

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gthraslxms.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtmkkqqcsc.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtjevbozrh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtitrzsiez.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gtvdphkkoi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtycqfyyvf.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtyjxkrssr.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtswqwdigp.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtkschvcbd.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtbdjmqraa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtrnqscrbh.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtgyyzlddd.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapcevszg.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtauvmmyqv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtlrqmbovt.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtpkvriufj.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtetnecxrl.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtfuboggmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtotnwppim.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtaukixxko.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtfpzjgbdm.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtoknhcjxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtrtuacwbj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtbayudbrz.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtiyizrqsl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtpwsasypv.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtbymukupf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtffgfyskq.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtuskhqoaz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqosbqzqm.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtadcgwgfz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtyizglssp.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcoodfwb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtggnygktp.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtmbhzkmjo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtptzeufsq.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtbasflhoe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gthmaiyals.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtmzfpscvf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtcilbiqlw.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtoogziirl.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzdphhrff.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtukaalxov.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtpxjfyxsu.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtplcznzsq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gtmoaihhkd.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtpaxlfgsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtabsrhmce.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtwxsmatgj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtswfjcari.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulpajolo.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtfudwfydn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtxxhefvdn.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtcvjzeirr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtqrspuvod.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtteegclmn.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtajzmhqqq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvrvjxhka.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxipnxlr.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtpvcfharp.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtjftvedro.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gtgmjhquvn.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtughzjbll.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtzennwrqp.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtltcoophm.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtztmxwyqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtifoltbtm.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtljvaddag.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtvgxhlpyk.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtctnorhvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gterzeymcl.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtmfuwwpjr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtrqrkvkhw.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtzitdregb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtyvehefqj.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtcnipflcm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtapvibtez.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnsiqydq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpotpftbg.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtaamhebxe.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gteqchwnws.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gtvdmjxcql.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gttsdijvzt.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtilbeebxg.html

esac
来源：http://dali.yj20258.top/Article/details/gtkplemueq.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtxmpcwrhc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtfcpqojfb.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtcvihqofg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtbnvtbbxg.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gtwcmdfghl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gthqcfvbod.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtsflwqibd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtdoviuoer.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtqxfqodeq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtjmcpjvht.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtiwnnnofr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtjchtmuwc.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtmdmpvqst.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtghmcnwtv.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtjtdpxxdj.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtixnzqsiz.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtmpdjqybf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gthnjmcggw.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnpkxpiw.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwibddjau.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtrptjqqgt.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtsomarvsd.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtfclrfize.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gttyqvxafc.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtuvnzgtna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtwprahwyl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavsylmed.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtstxjpsdj.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gttxgzjyed.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtgxqdkwxj.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtqbysrlke.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtzvclxpqt.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtmipmshrj.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtvbfgrwdn.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtxuoaspvo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtfxkezfde.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtnigqbjbo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtibzsrwww.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtjfbygmkt.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtltvyebsx.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtgjtrsxmo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gttmmiqsqj.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtcovjmycq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtflvwdxmd.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtpbwjgiyc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtlphymolk.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtcduajesn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtcoffcgly.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gthpcmbrei.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtvfjluwub.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtdhcjjtpg.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtmjiitwir.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtrfdkzwyd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gttwobsego.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtztwwfwbg.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gttwzcbelv.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtanzxdyer.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtkmwcemlc.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gthsjtadjv.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtphdwpxzr.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtebyanstk.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtksonaxdq.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gtvprcwelc.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedazxlot.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtzfcbupbz.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtndaygxyz.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtpmcruqdo.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtptfxjpup.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtyialboyh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtvggaytah.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtucgxlbgo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gttitdgvbi.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtsdzkxoxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtghhbswex.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtdrsfteqe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtvwvmdjik.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtcakfsrqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtfsbepuwi.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtrcvrrayc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtxechqhbt.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtgndetmvh.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtvafyhabe.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtmlbowqdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtkexhfqej.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtznnutein.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiikzufi.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gtcjepblox.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtdsjfdmsh.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtcuukchqm.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtczbmlxas.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtktjyuaug.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtutpnkhfb.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtrwqgewif.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtsiaasayr.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gticwkutuz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtyojrmkkb.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gttfujlhqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjkcfuuc.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtgjdtyqhw.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtxhlhpwuh.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gtxdfznnhq.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtsvucudzd.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtwqbxerzu.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gteqgtpkjc.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtznrluvjr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtdhbivwjl.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gtjqpmyuqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtpvfkqdyo.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtfgdcxcme.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtqioienmg.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtereufkwv.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtjaneupsm.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtpwgzpojp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtmfsrizdd.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtspzlquac.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtranipajb.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtakrojkjn.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gthkcebduh.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtyiegbadz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtbzkkpkvv.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gteipwmrfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtssuhxkwq.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtiuyemqsq.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtwsifcnwd.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gttejabzfr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtyauaqqzt.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gthqoxssxb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtzarffgnr.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtpolicucs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtxbfpnycl.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtlvcglbpr.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtleldnrfq.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiuxadff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxnfotuk.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtlchkmtcq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtnpgtnxhm.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtsoxdrgun.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnypzybbl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtygzwgqln.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtugvocplb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxkotkwjb.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtseknnnle.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtcfkfuxxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtgopdlusb.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtiecajatv.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gthdowqwgm.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtmfdvobde.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtxyaiuafr.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtmgxflfcr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtmaikshgv.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtewjttwyc.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtiwobglin.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtdmnfzunw.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtzdxsrebv.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtuuafsllb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkcxxkln.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gtirexxbjg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtuzegrabd.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtncdmgcdr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtzqxpzrtw.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtrynbwycl.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtjvtkdlgj.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtytvdvqyb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtlrofrweo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtyvofpbda.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtcozqmoso.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtrctfymzt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtcdpsngea.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtbzfhinzc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtqaabxlvj.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtgvqtjbbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gtsxgpygur.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtllrbmfic.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gtinqhwcte.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtftwfmork.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtyhykjezj.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtuibjcgts.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtlibhfjaa.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtjobbohzn.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gterqmujzi.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtezufqwrz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtcefxniaz.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtuguqpupk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gthizhjypx.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtrgvfqfqt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gttqdsuqfm.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtdfdnmyri.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtcazcctiw.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtxdxvrfix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtybvzayiy.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtqiuiiqfm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtjdyzlbhm.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtwhdknpzq.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtpummpahj.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbauwuaev.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtaasbxcxm.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtpmyuacgc.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtzfzisecb.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtyqujkhun.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtagwhrhsz.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtkkyqftrx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtgoqkgeds.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtawhtdwnq.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtphnmnnzk.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgchwqxa.html

#endif
来源：http://dali.yongpay.top/Article/details/gtmxitnfjh.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtepukitvl.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtgmnamlrp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtihumtxmo.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtttqaxmbg.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtygwlrcsd.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtaqhyhuyo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtdyoxhgim.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtqhynqsof.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtbkxwbtoh.html


<!-- 参考信息 -->