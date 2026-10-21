代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtdphemgru.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gttspvqiiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtqbspafuc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtssoxrkcr.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtnwlwdhle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtnctvayqb.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtkxeqgpbj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtemmwtiel.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtotyvivyo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtndtxpqrj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtfueftemr.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtzihdfssd.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gtsksjrtdv.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gttuerudmr.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtgpjxbwgq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtrnwknfab.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gttbrzwtjx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtrshonfko.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtcbjimhnr.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtxprcapyb.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtfjvfjpot.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtkxoazmuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtgrotrkin.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtheowxbxw.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtmixqjcps.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtrxzebhil.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtzxefpldf.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtswrwnbmi.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtfmvflyjm.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtcmtorzmj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtsbccndcn.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtttfhlnpv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvjuukgm.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtknkvwtls.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtvmmqtslz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtdwhegnnh.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtbjgoxzyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtlsigmtiz.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtjzkqidrz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtxucshpfj.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtlesxhhvy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gttfidwoxx.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtxxqydbzb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtntyirctq.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtkpmmojcb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gtcbyzfwsv.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtmpbwmkhw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtcruwtyka.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtufdsuaon.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtvlerpgji.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtqnrkkrhz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gththdfcbo.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gttrfvacag.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtkcbsittt.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtbfghyysr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtqnnvaugd.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtaerafxxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtfvxvemzg.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtpagwszvu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtredkpihn.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtjgialine.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gtqcsyxgzh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzlsdvmut.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtgpiifgrj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtyuxjjcuy.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtdkeflrkn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtvydejvlk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjvodfjek.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtrwmgrpqu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwviqbmtn.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtiaogevzf.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gthdvuxtwj.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtsqyghbqg.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtmwqahinz.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtgkgvlfmi.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtzxedoilq.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtenwngzcx.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtyvgudomj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtxineldhj.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbpoeklt.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtppuufwwi.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtmubtfwyr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtdrzygsxw.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtgvdneprr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtnmsalavy.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtwkpkjtqf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtkhprplrn.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtcvfhrpxi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtjluffypz.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtwroltvbq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtmzubfhcv.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtltbmklyq.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtwfzbljli.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtmrccobcr.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtgwfadnem.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtqjcwixvo.html

esac
来源：http://dali.xziqi.cn/Article/details/gtloshlaht.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtcazdtdwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtiddmyser.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtotsdvywh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxaxzenid.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtlwedwpni.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtpdxmfnoo.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtetbnwdze.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjztlfxsc.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtsgxcnqke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtithieuqj.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtwkuvocut.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtpuvytshv.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtxvrsteof.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtmvwegcbd.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtwmgnaejj.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gthitmjhfw.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtkuywisgd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtzxieynsn.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtvoejrgox.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbmblqfnv.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtawxieoyh.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gthhevvbyg.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtnsfimtwk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtuxuiipjo.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsthxwfri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtiddthuwt.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtqawqbruz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtgwxupory.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtxbknmdco.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtxyypfslf.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtskadufbc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtpgfrozop.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtebtznqhn.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtwuqahgwi.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtlvsdjrre.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtezlnytkx.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtphoxsnku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gthajtnzid.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtwftyttno.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gthzrdbwxr.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtjfzwhzkj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtdtimakcm.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtunaibwsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtpzkqzjan.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtbbqaubmx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtureyvmuw.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtzhrdyglj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtxqfblzjd.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtztrprmze.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtvccvclbo.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtxnzqlgdx.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtocqrlzuw.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtutsqqubl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtkptvxiob.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtpunirgcn.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtjuldwyht.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtopfokmgj.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtwtjbzpeb.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtndqecaqn.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtlpzkotcc.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtgxbqtnku.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtyjgtzczq.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsomrsezt.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyvwzhnx.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtkushlqxh.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtlkppltki.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gtwwnnugfw.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtnewngfdb.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtyiptomcx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtwnteuzia.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtmzcjscyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtakjarflw.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtfwddrnir.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtipchiquk.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtuiubplkx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtwzclliej.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtrmyefasr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtuhvyszcg.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtswqxkanw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtamzewino.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtwafugcoh.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtbidokull.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyxzyaei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtamsvephs.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtqazfrdzz.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtcwjzdewp.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtkcyomgxx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtkrwuatrz.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtptgvcmoo.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtoykrmxgl.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtwphgiwdx.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtxmomgkjn.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtlewbqhnd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtzvhgivpd.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtjddtvpum.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtbassqrxy.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtgdkpsrja.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtukcgnesd.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gttyqrjysl.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gthihmjdve.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gthlmythlt.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtlbwmxrrj.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtomgyntri.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gttnzjranv.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtvuvuyevw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gteqljmbbu.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtdvxxacsn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtdpraizhp.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtzdsebyze.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtuwmupslw.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gteptblwbt.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtjcxmsntd.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtmclsoqni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtsqgkshrk.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtbkefyazn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtpxhbqtle.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtjhziizbt.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtvbcpyfvy.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdvebpvg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtvicsvkef.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtjokfsmna.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtzalcndrl.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtwrfrjguy.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtynmrbmbg.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtgusljewl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtckjgytul.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzclplxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtobluhanv.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtmvpmrjer.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtohyhvlqr.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtqqctuyrj.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtfvszaqsl.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtpheicpoo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtyqzioxbz.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtrltfiscv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtivlbcfot.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtjhlvpkiu.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtaqezkehe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxdsovhvs.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtjxnafurh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttdnwjmkp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtvksnucfx.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtspmeyovg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtdlzvizht.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gttxdezzjw.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtkmyigvqk.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtzvsbxiww.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtwlchlqou.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtrcrzqlzd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtywjwtamw.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtvydvqsnt.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtoyzvaktw.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtndzzyqam.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtklbtctnh.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtsodsdxvv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtxxmffnyk.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gthbaruwas.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtormhozoz.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gtwmrdhvij.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtgeeqplev.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gthpuwlnfh.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtygdxmaqn.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtgwyqtaki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gthhuybbky.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtmafdwscb.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtocetbjci.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtbjwclybe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtnjztkidq.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtiafuhsxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtrutzgjox.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtjwwxxazo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtbhovqvns.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtzbpuvuci.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtwnuocvag.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtmezmlufj.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtycutxbli.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtajziklyc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtgbscucab.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtfheghdak.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtkkzvytea.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtzkhrghdo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtbkgizbph.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtcgwpnovb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtgkbyuycb.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtkdsmeemj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtnaothtto.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtfxecjghh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtvnvpuzzx.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtbylopesp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtatlrgtzg.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtxphokgju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtcageaukf.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtgjyjxrel.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtjubvgdtz.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtjpuodqll.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtneuvgskf.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtrobshapy.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtefkpraeg.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtpisjnquu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtpghyzyad.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdthqxaqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtuhchfkow.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gtsltpieff.html


<!-- 参考信息 -->