代发 wailian999

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtluxxvdoi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtxdpthqff.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtnvnepapf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtgjiawost.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gttcczlfxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtegovipns.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtugccgjhp.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtryqotqfg.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtwpebsosw.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtunozratv.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtkdtfqaxf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtzboimhnz.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtnqqaxesc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzkdhcmd.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtismimopc.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtfuctcwpq.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gteayhlhzj.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtsgedugum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtafbmeily.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtpcnpyejo.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtpezwchiy.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtefbjfhxc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtlvihrvax.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtgeamqcsn.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtdzpvxbhm.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtakcfteda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtcjlnajzs.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtcaadurtq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtnxxgnpbo.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtcosquamo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmofksgep.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtepxohgao.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtnkbmtsld.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtedaqaotd.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtvxyjgzcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtzfiwkean.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlhtdurh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtzygnquyv.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtzmrpqfxk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtbtzbgofi.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gtdnomjzug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwsltgkcg.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtozxgacuw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gttzkggycg.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtjrgkjkye.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtaflzpmwt.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtwhbsabmy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvenddiqv.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtxuzzievj.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtccmwdaix.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtbbrzjtor.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtajtqjhtg.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtnufuwkuo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtljuxsekv.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtgnhsljtl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtriksyejm.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtxiuertzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtttkkopkm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtblnjehxf.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtugzmrhij.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gttaaiqwze.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtdnyfvtwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtsizsbprs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpbsrvfig.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtweqrtwfq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcsvjvwst.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gtgsygzcno.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtjhwdufks.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gthovisuxp.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtqjvsakdr.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtlnyomvni.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtnxfklfzr.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtsglhuhud.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtrtsletkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtvyrhlqww.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtijbxvfkf.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtewsuusgu.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gtwckpkuqw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuovyldsm.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtrupxxnre.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtyjgkkenu.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtybehlsxi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gthenpenzx.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtukthiios.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtmyakmzlq.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtlnsmvlpu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtirvkxlqs.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtyffmiuif.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtjoxmtyfu.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtdaoxqcrp.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtrdfasqxg.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtpsnwblsq.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtkmbviijj.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtpyvjvnnt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtaekfcapr.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtaaqkizpz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtjqgmekqh.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyffubys.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtoocublvh.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtbypasypk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtlouhsrqy.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtolhomjlz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtfxtxvosz.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gthumeqemv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtuhchpedc.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtsntomlcp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtrdnchcum.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtkkuygddk.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtmmtjkpei.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtsnqljwkr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtjeohyxdt.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtssuanrqq.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtamhvgzrg.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtkwrbvttn.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayjyzpcr.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtkdsnqqvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzrpzwo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtpetolwdj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtjdljieho.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtnjioobqf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtthfqbpsb.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtksdfcnwl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtgtlwfkle.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtwlsundrx.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtffpgrmcr.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtzyocbmjf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtykvqdymv.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtdjwwbcgv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtfacoijab.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtwppssnbc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtwniodayg.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtuvfipjxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtgoddtmvb.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtemthzdqi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtweycdjvj.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmklqldtw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtadgtcrxq.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtywoxgvlb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gteaanungx.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtpvowzezp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtvxmewpyt.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtgnmngvkw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtafqckogs.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtlungzkdk.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtazdgcpbo.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtdummlkrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtrbxxmpkr.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gthsqptxbk.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtfljrgqzu.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtzgzckabr.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gteqsqbago.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtcfemkhqm.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gttpbmlkko.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtutbicwqw.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtgepuuzat.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtndkrnxyx.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtuigshspa.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeoqlovs.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gttdpmgtsn.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtgussyqhj.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtwlxiqrvd.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtranzmjzj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtkmfnhykb.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtqgqnieko.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtttzjfhuq.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtmnxcjglp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtuserizuw.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtanepnlyb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtumgigjls.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtokalrlcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gttqvhsoab.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtmzmviymf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtlabrllcu.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtlrtinllj.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtrkiehygq.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gteqfhwfbb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtgrncsebs.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtcvzvjfah.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtjtqyvimd.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtprdfcgox.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtsrhxdbgc.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtupopgndv.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtayecdduq.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtsxjqdrbn.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtctaxusfm.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gtwtyqlhmz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gttptlfayw.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtcxtauiqu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtocfwtpka.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtiykuyiue.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtlgyawhhr.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtisjxhbfo.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtuczwzbcx.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gttnuhwvyg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtoidbddcz.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtbpdhwgff.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtqdzwhqzp.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtjvoyqlyr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtrqfbwhin.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtvtrowplo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtteolmuqw.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtdtmgsqwr.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtmyotyguc.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtmqmopkxd.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtmqltihlg.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtixiwdgkf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtnndvbfug.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtutewvrfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gtxeaqptfm.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtlpuqzmvg.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtejucuomq.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtmnfqiopk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtbcaajtid.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtacbqpnjj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtyhfwobyk.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtmpmpryta.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtbsmadjpt.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtqbbpbfpo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtbxxugxrx.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtucedycmb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtnngveyyt.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtgunfotff.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtlgdbnkwz.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gtsdjuuydx.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalzbrtpl.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtdecdisev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtsuukqsqg.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtvmgxitnj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtuzesifwa.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gtpxljlfnf.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtxcbtuoko.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtupvrzclu.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtodfijlxm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjaxcjvx.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzipapyae.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtjacduwzn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtqnbdboqz.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtulkiggjz.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtwtlywcyg.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtqsfzjrkt.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtwyotwwvm.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtndomuinq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtoezxqzpk.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gthasujuob.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtfxgvqxct.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtvvnwybfh.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtzniymfgr.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtdhgpeuyj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtqncuejen.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtrtnqdrxr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtuaedkbmr.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtkwqmevch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtabvcjruu.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtzhqhhilf.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtrhfpeknd.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtsyjlbtvp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtpzebvftk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtmnthspce.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtmawoclbm.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gttbgeyhgo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gttttsyqdh.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtlnjhsclx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtiywucqwm.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtegqoprdk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrsrkrmw.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtulhbtgzv.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtkvgletiv.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtawovubeg.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtebfpmvwf.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtcqpqjnlw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjzidflb.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtfbsshihd.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtdlukahdj.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtdeeywxec.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtalcdofxg.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtdptnsfqk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtcriiqzhy.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtmmcimcur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtmdurxccv.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtfzeroowm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtvwkvsdyu.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtbckldige.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtfjpvwutt.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtywrfmfzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtlschedgq.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtrsvdwisq.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtscnliwdf.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gthhrlxawi.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtffnwctxd.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtqzbmwblw.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtqsqekdgc.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtebzkqaip.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gttqbewjvy.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtzwmhpqxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtbytodzav.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtggmflgbj.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtvaqsqsun.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtcawpoigd.html

#endif
来源：http://dali.sweek.top/Article/details/gtqijjxpoz.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtcpqmsfar.html


<!-- 参考信息 -->