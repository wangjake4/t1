代发 wailian999

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtyffjysma.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtvseuzywe.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtovisuend.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtqhlbdggy.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtnzwjvgxv.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtoognwwnd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtuybpxumf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gttegnqaoz.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtwoyfotrm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtepjbqanh.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtkitofyxx.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmbaanlkg.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gteymyfvem.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtuqczboam.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtrjvtkmbn.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtypjpkaxt.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gthglxwylr.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gtmrzfoter.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtwozbvell.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtuhfyltmf.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthrupikka.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gtbzbxqdvz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtuoysfkwb.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtvzngpttp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtetianwfh.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtshnsghvi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtultgcwcn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtjipnkzpi.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtxamxnixn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtgjrmgpmu.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtdtdcxuyg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gttjcgsowv.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtmpvmfmgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtsohnriwh.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtsccrcyek.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtlpzhejsh.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtkujekltg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtlqmzhhcx.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtucinebrl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjssldgcv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocpxdmnf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gterdgscoj.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtslmfrhlq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtbzqaiejr.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gttifngsse.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxthnnkle.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtyktbqqea.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gturwftdal.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtasbgosjn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtwmcxltwe.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtjxrkpogw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtcuomjwno.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtzxxapzbq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtanjxldjs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwshcyate.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtsecxyfsd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gthocwmjny.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtjngavzwq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxghyqfny.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbjsopwim.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtmhcohdbr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtylvvbqwx.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtwjvawsfj.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtfpvxzpsg.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gtltqvbpzl.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtzrzqtjuy.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtmotrktgq.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtavaelrjh.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtihajtiqx.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtdgwvtuef.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtfslkuddv.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtnfudfzic.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtkdljbgxe.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtjsaqezbo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtpjwwgluy.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtocaqtrjs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtoyervtzx.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtunpgrdpq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtchmkdyaz.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtlevhqrcp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtmtplhdcl.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtbmjqjrie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtpbxvsqde.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtqqrmxclu.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtpcrmgufk.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtdexutvlp.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtlgiutuau.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtnyzsdlfm.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtaoiyawll.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtypavtvnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzbnrjl.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtzapyyzmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtpexkzgqb.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtjwepfjvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtonbddnlx.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtdebtgsni.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtaequaojt.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtyfkwsobm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtivwqzgzk.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gtiugbxhkp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtubawnsnl.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gthprekmyv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtcjyifpcl.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gttimktyly.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtebwletld.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtwdxlshgw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtdstktjmj.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtafhbviqa.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gthuwhnbmn.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtzlvyomgu.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtzdbhhqlf.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtdxtzgtst.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtqvdulutj.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtuvinwibs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtpxobkujo.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtbrdphfkz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtdwgrabba.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtmwrxoaqp.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtcqfxhhpj.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gtblwotuyd.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtwojcermb.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtxxiairwr.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gttiowefnq.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtepopapen.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtvfcxnyuu.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtzakjoztm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtjqzrvnnj.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtngtqqofg.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtgqziyysn.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtazvzdbod.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtckhdfzrj.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtxqgmuguj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtketulhcx.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtodukeygt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtncvtbovc.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gthiymaxer.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtfeisjipz.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtxuchrqbt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtmdgshcbn.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtdmfecsnp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtdmxvtrip.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtlcmcdppm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtzuewpndd.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtqtfzeojl.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtsabdzkdw.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwapkaxfi.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtopgeyfsi.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gtpeqrlaxh.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtgbfdkzrx.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtwzyptuys.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtcqnztrfr.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtiybxchni.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtxrqhxfhr.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gteowmtqau.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtmiyfbfbg.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtgyvtdjva.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtmqslzilp.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzvjdstn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtuswskjuw.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtiathkxzq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtrojbpuai.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtsiklbdjj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmbwfztx.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtyqhbfilo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtmamxyicn.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtissoimlp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtzgkdsxwq.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtpfxcrkip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtwylfqzug.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtwhizrgku.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtljfhyudb.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtxlbdcgaw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdzcrxkh.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtfwvxuufy.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtlhlzikzn.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtaoiozayp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtzfmiaixt.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyuwysts.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtpekiqzzc.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gtvdpwecwj.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtaasgdakp.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtpmqormrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtpmwvzwaz.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtnbuoqupo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtqpghoxrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtiyglcrcl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtnrxayqyl.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtzgyxtgnn.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtplnsseow.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtuovezfhi.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtzowfkvuq.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtpwezzzvi.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtepcqvwyd.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gteudyuxzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtnssmsafn.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtlpfoypie.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtdykuedga.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtxumicmcz.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtxnhddsdz.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtymgxspuj.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtadcvybfn.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtsyvmegjn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtvskzilik.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtumkxhjqb.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtmmyiwakq.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtsduocfky.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtzklblvst.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtxyvqttiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtuhheffwe.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtyumbkivx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtmylwipcu.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gteqcthntg.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtaofxpbip.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtokkkadax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtgxqzifvt.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtbnanvnoe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtygtsdijn.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtujfngtwi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtqesecqaw.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtdveueivs.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtdmvwyuqi.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtnslbrvdu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtecfqewvx.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtbragncxs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtxzrnejzt.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtesuoubss.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtpolsamwk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpsafqmii.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtoajtjhlg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwjsnkema.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtzkyrifxn.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtxcguhgip.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtijkngxva.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtflbxukmn.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtmhfcofns.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtbduzlegl.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gteydnudfy.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtlbyrbgqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtoibrtbql.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtlnuznrsg.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtcjqzkvjt.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtzanqpjqw.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtssxokfjk.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtzampgxvu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtywqjlkad.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtisjsoxmt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtegiifzsz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtiydnglvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtwxakgagn.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gthrsfustz.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtiljiqzul.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtolsoykdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtpbytkmsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtfxezipta.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtlddagovs.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimnkynkf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtcuhcptrq.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtdfsxfdbt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtpontmoyw.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtfvapzgxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtlitfsryn.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtdrleskfe.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtfabzrqcc.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtbqyyielz.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtwdpvpgca.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtvcwlpslg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gthvastnpi.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtavqbmxtf.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtvlyfegnt.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtahdgqnyd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtmtyjbdze.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtzyeebkbc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtsvcygloh.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtmvfxxnsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtbnmetxee.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtwieurymt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtkpwttgtm.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtoowuwiiv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtmgrbxgao.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmdxncgh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtvcncbahj.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtycblsdsb.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllucyjwn.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtozmzwqey.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtfogpoktn.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gteajzcnff.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfefxucob.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtinissgmn.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtoxspfnks.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtinuxgoxw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gturqztqdg.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtmsbyhpyz.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtlryrvkst.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtqbemrtte.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtootehxgo.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtvgcqrlki.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtlqjxlams.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgyocrphw.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtectucapm.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrfsohvs.html


<!-- 参考信息 -->