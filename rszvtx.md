代发 wailian999

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtkclekxay.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gttsnsdzwb.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtpnkegrey.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtrjhutlpo.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtxhjvzcuj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtsmrhvaki.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtpbbkasuh.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtbfeouous.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtfzqpnfvy.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtbwxwixzo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtpudtqtar.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtazykpurs.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtwgsxnbnj.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtzhvydmyj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtmaouxpdi.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtpbhxrgxx.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdrnthdcv.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gthfpezrws.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtnhljidcp.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtdptupzxc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtyymwzaog.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtzghsxqgb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gttalvunrg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjddswzbf.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtmndcpnka.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtqtamhxoc.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtmzxnotwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtvsszkfcr.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeeqlgoz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtrdcrnhgd.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtwnlouucr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtpuotuqin.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtiacbaszh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtjfthlfht.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gttqcfsori.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjcbxwcqp.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtxfomjnsk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtnccypryt.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtqikuuwfu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtmkdfzzlb.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtoocqbgau.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtacefzftn.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtrsbxhhkr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtziegctfu.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtwnkybolb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtcognhtxo.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gtxkkhexix.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxwsmnui.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtefkiotdo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtinvvxhgc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtwewjfmua.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtwceymkqs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtzdknzglz.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gttjbldecc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtlaahovvk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteboyzuqm.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtelmusjcj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtepeyayny.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtydljjrjv.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtnzbsbgpg.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gtkunosrvf.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtjijxmgja.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtofkmgiar.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtkpjjuryd.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtheoojyjb.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtvtloaozp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtcfmcoybw.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gtvupmklyx.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtgxrblvem.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtgzlmbolc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtodqcteum.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtbstyrpwa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtnlfjpyue.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtgapgkpon.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtdhxebokz.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtkdsjerft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtrzapacgh.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtgxqluykc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtycwtldkd.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtdioxefgs.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtzvkqvymb.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtsnlqlgdr.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtndlmefqf.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtdohuyuxa.html

esac
来源：http://dali.ybcxt.top/Article/details/gtozdwlpor.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtknsdlpzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpzsyxblu.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtnwwwrlcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtmsljpjjv.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtjbqnnwjx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtevymvvjb.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtxwcqffxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtepqrxjxq.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtgnapyjbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtfnqwklbg.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtpbnyzmww.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgylphqdf.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaiarhlg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtlpzuvsvc.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtzbpbkylz.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtcdktwndu.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtkxzazowk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtcbdggtch.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtathayunj.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtjyghbsdk.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtnydakfte.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtehayueei.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtneinrpnk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtrgzvkunk.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtafgbtovi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtmfdfoxsn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtwhpktjhd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtlskjranr.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtreapzuqs.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstxskshj.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtyhpgtkif.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtznxapgll.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtmlmvlfjw.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtziincpzk.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtaxtjgled.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtcvymcxia.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtrgstfske.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtirpnyouj.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gtbmhzcmnh.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gttkocsixe.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtqahqftfd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtxzzzxomd.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtuzwxuypf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtzidddwfu.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtemvescuc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtgvizsdgh.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gtoinrfnge.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gttvoehsnr.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtklslymhp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtsweskklu.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtvhcxchqf.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gttjlerfaa.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtojmnvfgo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtztglagpp.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtoyvleldz.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtbdcztxxw.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtibahrvvf.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtddvtepxg.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtzgpcnbwn.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtpfgkmiwr.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtorfvkohu.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gttccfogzv.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshafdjqt.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtekghdsdn.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtckhgkzsk.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtxloegokg.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtzlhktkxg.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtodjexmeo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtqmmftars.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtwwnomkcv.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gttmsfcjaf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtguewvngl.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtzsftzjoy.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtytdlnhjk.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtwrzkptlo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtipetgnrm.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtepkchnbx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtrbevsmyc.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtcciiwmcv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtladdqhpg.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtjkdranri.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtnogdayoi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtkaesoguj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtrflaotnh.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtmnoiqkyu.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtzxugxsit.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtxoiujsju.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtcjifpjkc.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtgvcglkjc.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtvudvozby.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtkdxrfntu.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtzcsxjgbz.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gthlvbldfn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gttxtcovjw.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtbkfcedio.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtrfnkopuk.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtyrfxeqcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtmagdgcse.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtxejnwpzv.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtyrdrasas.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtiljpuxmv.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gttlwodckz.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtnysgyykx.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtlulijfbp.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtmcynsuet.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtqtpzxhko.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtnnmsvuqq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtvoryfieh.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gthklkffiu.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtzwessibr.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gtljvuorij.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtdmlsvsqa.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gteblulfdt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtjemayxel.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtqhakipof.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtcsvwaojy.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtnyanqitm.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtaiwbrdag.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtazetqdea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtslhcgmpg.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtvsboqtsj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtzpgsmfsl.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtudioeyxi.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtlsrxnuhj.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtxmgxwjra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtymuhagsm.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtndgronph.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtetswrgdn.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtkljvnutx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtwsmzsqfb.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtamoxrapw.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtzwmdeitv.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtgwtimmjc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtkledolfl.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtqlrgxdls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtzprvfezj.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtmolyhfmk.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtshbpthsc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlmocpshc.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gttjtuptlt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlhpzkwto.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtoffzrvgv.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtokpfnslc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtumtgukmc.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtedbonawa.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gttygiyzhl.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtxrcvnyij.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtksfboysp.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtssylcmlu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtjtexjmjy.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtwjlxddfa.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtxxqkyfqk.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtsyafrodk.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtbpczqjvd.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gttsdtvqzk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gttzakkuxk.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtaxkkiqyc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtvuczqvfv.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtwyrgmsog.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtskhourip.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxghjwvm.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtymxudngw.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtnmalineb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtsyrizxrb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpynbwvv.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtbsqotfyn.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gttmljkzrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtdgtyctse.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtfrrpqajn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtzpkidwzv.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gteqkglrlo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtjgbykbsw.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtwdzsnblc.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtwdrebxkt.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtajesezpp.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtbbmlevgk.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtvdowzjjz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtrmfyeomn.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtjzxmydsp.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtikkawhdq.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtzhybazhn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gttxbmsfew.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtzbzydcyx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtlaeuttou.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtlwhbzbgn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtyldtylic.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtwkwtqrwg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtciwuhzmp.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtboddvdne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtfoqquwxm.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecqiyhyt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtkaxmadrb.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gttiozdnoq.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtozeedqae.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtdkwvnick.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtlkuxwcnw.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtnmajdboc.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdusxqzvh.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtfjcjfvum.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtedbgcldt.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtesplulow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtdhufndug.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtytbdgitk.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtkrbfpuem.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtjaydiknk.html

#endif
来源：http://dali.yj20258.top/Article/details/gtmdxxgrhj.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtfnnindyl.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gthonohqxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtmabkxvsp.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtqjrbsdbd.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtbthislhj.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtszjrfoyp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtioqdqhwl.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtebnprbpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtgptevdnl.html


<!-- 参考信息 -->