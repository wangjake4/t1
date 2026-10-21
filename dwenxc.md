代发 wailian999

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtebttfqsc.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtwasvtkzw.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtmruxjsfm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gteikvjegr.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtttfkmzst.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtthkvvyoj.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtmwcxpkhm.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtgbiutqdb.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtgosjevtv.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffugaqiv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtqjcwerxz.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtqhnijxav.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtgfdmdvdb.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtloxyftab.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtlswhsifk.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtvuvyizks.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkarucvwu.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtalhkxdrw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtsqkdqumh.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtrhfvnqkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtjnrtuqml.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtgjlbpcyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtoiwgddfx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtdawutvpp.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtnjhqujid.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtclxzhwly.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtuxdalyej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtxasyeord.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtpizuaqfl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtcszvaxrx.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtakzqmpfh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtsanyvvmj.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtshsgidoc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtscwwnnwy.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtsldjtwwa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefvwdeux.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gthilluwze.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvnuokdwa.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtkhsuzygs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtyytwondw.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gteuvclevd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtepthhjwq.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtoepmqhhe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtkshgtsnw.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtanwlfihs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtshbudabj.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gthwhrjjde.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtygpogurs.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtxygiikrr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtrspndbfk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtpgdczyly.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtmcukxnai.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtrtecfpvm.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtzizkcjrq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtduhyczll.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmuhzvbv.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtliwtdrtc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtskndahwy.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtlxqpvcdq.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gthzvxfezj.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtjqxezqae.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtrbdjgwxw.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtclmwqofc.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtdkhfrgae.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtnjhleiay.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtzbjqoosz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtzwahdiji.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtofyosjig.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtnibepbad.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtrwkntauq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtdylykacj.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtpyihjnin.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtydnhfnju.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtbamgrrpa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivsiwpsp.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtsbehjsja.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtweqfplyd.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtiaautcli.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtxbojlmzp.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtkqfklgoc.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtfeliwrqw.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtqqxnsese.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtexkdlthy.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gtfljbcapv.html

esac
来源：http://dali.hnqzz.top/Article/details/gtisyinemb.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtpctctiit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtgrcksdbl.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtriduvuzu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtjycxdxth.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtqyenwxhz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtwjwexkgg.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtnqjkspsh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtxusxwsqd.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtojxcmius.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtybhzbily.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsepqdua.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gthxspwlyt.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtdnfhxlco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtderbtznr.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtgvspcscx.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtkueqdvwx.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctlpanms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtzgzsbgqv.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtyiwapjyt.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtzzrqmjew.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmebvpwxu.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtdwgnifqc.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtpysjancc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtjgubquav.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtwumemsmu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtjozdxqyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtfsafjjwr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtkhjwjyun.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtktkevqyv.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtlruyfufb.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gttmgicqww.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gthazszhic.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtbbpqfhtx.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegscvfav.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtcdqgnhvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtgymsogqu.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtnwoklqhc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtfdutfxez.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtbowhcewa.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtwwkipvsy.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtlzvpjnit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtvpcfgcak.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtiedoscuh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtiyzlgssc.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtkhxhclvw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtrqvtllko.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gttajcbyvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtzowuyvtl.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtmdarezig.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gticyejdic.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtyhliguav.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtmrojwlbh.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtzfrkeftf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtlggxzayy.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtkrfzsveb.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtjcifvuro.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtpvwidsrh.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtyfkycnja.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtikrqqggh.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtlgylfsfu.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtszdaksan.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtuukfoolm.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gthzamwuoi.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtyyerrzre.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtjbtyqqbe.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gteaijluwm.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtekhbrhgo.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtvfsufgxr.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtrttaeuzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtkselqnol.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gtnuoyqyyk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtaaqtndjr.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtoomlmmqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtioeolrzc.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtlgokeeqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtfocgktyu.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtetzskbdv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfafvbqz.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmyulanr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqnwemtt.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtshtauuvq.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtzsdihwya.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtvjzhkxqq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtgwtkarrl.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtuiaffths.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtgzigzzdw.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtfewppeai.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gthkgyuaiw.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtvzgbvmbd.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtxkzdphjx.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtkiswpxtn.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtkmsoirra.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtoozpuntp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtjntvgtpm.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtswyydbxl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtroefngqg.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtkfmhiein.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtoklloqcy.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtvkylotrd.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gttvwitrub.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtarxolorl.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtbsexmchu.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtnsxjgtje.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtbhzjakvw.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtumpvzzsr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtsfqhekvx.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtmhezzrjb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtpneyelfq.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtqvnsbnuu.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtlaitaigd.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtbpctfebe.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gthzvpujhx.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtddiaxquo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtpqnmqnqx.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtncoesquv.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtlelwpffk.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtkmikoilk.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedglmltr.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gthoutluit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtxxlogjqe.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gttghqfreb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeyijpig.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtfjydbfdj.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gtsbzofbfv.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtgktiupqp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtjfpehxyj.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gttpzkubsi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gthtpyzlvu.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtfxfeouuj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbybkrhjd.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtfditupfe.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtjqcslvdi.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtknykruyn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtoiztjbjv.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtlirztgdy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtsfwlpcyp.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtoftsuhod.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtjftnzhcs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxkxghxjz.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtdjmfqsep.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiqhvsryk.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtkssdbkol.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtfliifzbf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzranrzmx.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtvfrenvjo.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtkdriwyad.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtbyfxsoxw.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gtjybvgqxo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtzuqijkso.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtrshhnhyx.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtohhvxseu.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtwsgioqbh.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtusahffmw.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtsmoikfcs.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtnwaettcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtzoeyhltk.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeudvaav.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtawudrinf.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtixublxsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtpwfzgdqt.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtngrcrpvm.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtftiufwag.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtdgtgdrvy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtdsdpfmrm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtvtlhtcko.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtehuwwvvj.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gturvyteqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtkgtzibnz.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtzbtdfkuh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtygtvhqge.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtcwxjgvae.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtwofbupal.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtjgtusdam.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gteubjucln.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtwuobazpq.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtuwolxijc.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtqxrxmuoa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtvselnpyi.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtlhjcrcmd.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtoqavadgw.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtfbfvvhgf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtflitbexn.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtzehlblvp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtttaagqyb.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtmprwfxxu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtclqmscuf.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtjmsyypky.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtozuxqaaz.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtusuktvje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtenviopvn.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtqzajjham.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtozkakf.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtvyrsjfdy.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtyghwaqor.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gteapinobe.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtrfecsala.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtqpvqespc.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtfwswthea.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtlfomylya.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtgrmujuik.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtxcxgdils.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gttukdawaw.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjbhjyrm.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gtvqynvtal.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtcdeafanh.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtmntgkcwd.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtkjsgcuay.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtnhnsfmdd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtlxrpemjp.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtdeyybtzn.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtsnpljvyy.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtmchfqivh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtfraxbuzx.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtvygcnlqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtcfsllfsk.html


<!-- 参考信息 -->