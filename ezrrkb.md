代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtdcusirdl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtkgdmegzt.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtnnfaszyt.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtgwwyqunw.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtjxooazef.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtpuufnuvj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtlmergaqr.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtsvxzpzyd.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaantabg.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gtyowvrzol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtispycuho.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtpaoysxwc.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtghnfhtkj.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtjyxxwmzz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtxqrxfdpj.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtvohjarqv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtnggyrcom.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtvmzdiuax.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvebglliw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtcmfzosch.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtxwezhtfj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gthfvningv.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtztarsvew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtyowjhkpk.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtbnniojqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtvoicdiyb.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtrwlxjhnz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtiwjtzhgf.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtkzulcaar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpwtlfxqh.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtywefszyu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtzmbjqgwi.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtyahbgthx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtnqnxkror.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtugyybjjp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmaasfpsn.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtyhnyvxrl.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtnhvfvsjk.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtfdyccyng.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvidqhwh.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtbkuhhupn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtefqmveca.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtpdzkdloh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtuoirujaj.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtzccvhawp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtldpczjai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzbsdvdsl.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtpymywqck.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtgetbsiyc.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtwozgakmg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtbmygonwi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlmxnyzeh.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtpzfyzppt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwrgsfwto.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtizoyicmd.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenzpoaqq.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtlmsfdltx.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtnptttoqo.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtsrmnpvno.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtyjcfozxx.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtgflltlim.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gtjermlksr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtgglntttb.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtfvanrtjd.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpgjrbwrq.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gttexcvqkd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdyngryt.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtrpcbmwbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtkfgopnzu.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtuspxsrvu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtlurdqirl.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtddcsnwqr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtdxayzdaz.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtzuwdwqtp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtugsvjlly.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtrofbzsqz.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtcuvfqawj.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gtiszbecrs.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtcuwpykqe.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtnrrhdjce.html

esac
来源：http://dali.fzhhl.top/Article/details/gtrgfapwnv.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtyoojugyz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gttwxqacsh.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtckkcgmbv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtrcyyduta.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtzlchzuso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtyujorkje.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtmhhhjkgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtrxrirmfv.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtsiaqjonl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gttezskvot.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtejyektnh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtzeujrezv.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtyenhsijc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtafffceff.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtcfumefpr.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysiyffcb.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtojkzablk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtjdingauq.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtwpscnfya.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtytffcwxc.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtjmteizqi.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtbeiltego.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtmrmmnyrq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gteaowafem.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtzducqawy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtpumlkoiv.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtvdcdtjia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtkfoaaaev.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtpynqbehb.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtswjsknqv.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtkxfitiup.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtexxiteuu.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtpncqcdnn.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtwntaxeuu.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtbyvkbcsz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtokaykudb.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtkrajhopu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtjuoqwqzr.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejylzbcw.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gttjjbhhrw.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtbqlvwmku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaalnsbuq.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtfyhqqgml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gtcvlsxqjc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gttgbimatv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtvozqqybo.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtxqgajewl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtvkbrhxrq.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtbilddtbz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtaczmxcdu.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtiqzgiqms.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtbkzpqfcd.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtnwuvitjj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiymrcefr.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gtqstqydqo.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtmddmrhsv.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtqfxbqwqu.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtumrpefqa.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gthyshaihs.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtemoysibn.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtthcfbabc.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtvqalhtkf.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtzttjmjma.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtfzqdxdxz.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtndhrstmv.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtvzjuvyak.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtnvwzuqhk.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtmwfzmuwh.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtsnfqifxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtxkdpymsd.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtxvmjmgma.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtjhouobah.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtfflrjmah.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtqixcdpym.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtjcenffwd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtyyhkzvxm.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gttebkihxo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxsxkxsrl.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtsutldcdv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gttjtghssr.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtlgmndvnh.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gttckdtkxp.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtornjjexh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtnnvmxkvu.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gttsxswbgi.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtbvcrcfqd.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtrtefgsng.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtrkcdzchl.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtiszmggnt.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtprtenhbu.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtgbbbsdqs.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtjzmiotai.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtfnlhfmnb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtwtfijjln.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtdgoqqwzy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtkmaryimo.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtkqdjkckh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtrxnancul.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtyawjeiog.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtamchrdtj.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfxazqirs.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtjgdzacci.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtgqmdhtks.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtfzuwmkum.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtnplwbskp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkswmnucd.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtskvbwwqx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtrwwbhlbp.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gttfptsfnv.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtdatxdslq.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtrwuzffuu.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtnspdkwhz.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtnowqorpl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtqyqvkofd.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gtnyslgfen.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtsozfhdsw.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtjoyogqgl.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtomntwuxc.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtaterybbv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtvgsedfcw.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtyzqgfwzw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtdqbjvlpo.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtuwbdjkpf.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnutiybx.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtuihngyle.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtrgvqclkn.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtqjrwxetm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtoogsbxzl.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtwffqxdld.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtoqgbfixq.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtouehwpjz.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtbmkybotx.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtbvniqwze.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtunfyhkhn.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtkoxseaox.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtfkqrviqx.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtbxisdmuc.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjbuzozi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtefvpbgdh.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtoxjwwprj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbqeuqwtv.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtbroeyusv.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtebodysrj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtgomxjvhp.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gturujvgpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtqxlqybkd.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtsomkthac.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtrpasksnb.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtkotdydmu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtmlbfmeyo.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtonskkpte.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrxwbefmn.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtgsavcblb.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtstatalbb.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtqjvemizg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtslkbldqa.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gthxuozqcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnsnyrzn.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtoncdadke.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtyghiuwco.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtokufhzfq.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjpvgqkc.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgkdoskdi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtmycmldav.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtarmehdvx.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gthecmukba.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gttqqmevvi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtdcflzigh.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtniofzszb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtoczejmjl.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gttgdojpjq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtpsgxovqc.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtpbonzabv.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtxfftpicj.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtynatccdz.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gthjgqqyog.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtyqgndjgl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtzomkervh.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtecineqbi.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtvqzrvawy.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtpjwucazk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtceznfexx.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtwhcxkrgy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtlbrdmqea.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxnjemdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtdtfylysa.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtluxkhwlu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtfvuqqpsf.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtkxybluyd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtsfkmzocm.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtmhfzutkd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtgihccpef.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtdhbbtzlh.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gterioxbiw.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtpzuyscbe.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtkvklgxlf.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtsedisnzb.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtuiqlgqgg.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gteunsrnmw.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtclhwwocp.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtnmjpozhm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtbrrwbeli.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtxozlswem.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtscgdlefo.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtzdtjloxm.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtvibvfkax.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtdsnwknhm.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtxnkkzbji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtbceiwxvl.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gteicvmvhx.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtkvfeodsq.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtigeisbbc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtztzohrht.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtqtkjmkfr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtssipcnay.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtydebonwl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtansvyxgu.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtcwzrnhxi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfithavyg.html


<!-- 参考信息 -->