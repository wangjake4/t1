代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtbschpbhy.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhyiotoo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtahsxepgr.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtpocuxxzq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gtlwhmkjpb.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gterlzfaiy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtxqxydgte.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtsqljqnmu.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gttbjfesli.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtetbajqeb.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtvzshqcqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtdsinrcpd.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gthbrhlvgq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtxomahhzw.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtkonhtnka.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubagajqs.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkazemguo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgsbetazu.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtloyofykm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtsrczfqkt.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtxprsypfw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtmrjufhei.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwyqkozu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtvvarfdcg.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtcjiotysb.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsgecsitk.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtioxfafbn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtzhinhxxn.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gttwdgjjfv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtfywgefit.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtrqczcvoi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtehhqahig.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gtrysjfpvc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtxfdkndbp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtcunqroue.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsjxqjzi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmyvuhhu.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtsmezhiue.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gthnsiozsa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrmcggkjm.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtrwwpduht.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrtogxawp.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtsrycttyi.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtjhmitaby.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtsyhlzwim.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtijnrqmor.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gttpgnpvbt.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gteqmbjoys.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtohoeyppx.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtvgqjikba.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtidrkuwjj.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtwlberfam.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtyxobmzcv.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtywpihhyc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtyhtiixaj.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gtlqfxznzz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtjwzwwavd.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtfwukwxzs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gttizqfosa.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtnhebfjcp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtdwqtvhzx.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gthwgtpvia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtbfzvsuis.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtipnewdln.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtlvkoevpu.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtvatehsyf.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtgiqcutvz.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtvxbyhsnq.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtwaxerevz.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtwlwnvsfm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtgiyipjjs.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtucsoubkp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtszwxzmrh.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gtucvneyyr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gteoperbxm.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtdfkkdyrx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtfhkyvadq.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtmybhgsei.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtzhhxgoqz.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtqbzpuywc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbwtmibp.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gttuwcjzjg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtxpfvzpjq.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtaekhjuok.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtijlvzstj.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtdocdwcra.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtudbzvjag.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtwulrstyd.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtfpseffax.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtpbrjlvnr.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtopnpkspn.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gthpoeopuz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtxlmkcedd.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gthovavssy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtxakwvone.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtgrqputgg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyvxsvcc.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtkzuptjqs.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtbhlalofp.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gtpmlrteym.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtuvxaypuc.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtczjsspyb.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtyznjbydd.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztennfnn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtgnlhhzkf.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtxgokamey.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtrawwuhlm.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtlagecjws.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtcvgnmxmy.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkehvouef.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtlehjxslt.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gtrovtgpee.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtszgpoojx.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtvlyznhzr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtassmhice.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtzlkfjzsg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtispfdbsv.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtxmiaxsio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtljscdutt.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtzicrttjg.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gtadgbmlra.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtbbmjeeek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtvfosezft.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtdjmtajzw.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtdnslwcmw.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtvyienxeu.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gtqjvgwnzi.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtgtbariye.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtgixwtetr.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtawlmbzwv.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtidnutanm.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrjezlkao.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtixetgpqm.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtzmenmcus.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtiwtwrief.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtyggtxyic.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gteqokhvlz.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtacrydbdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtzmygvizp.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtsvypqteb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gthxerdees.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtnzuxrkby.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gttxhwljsg.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gtzljrowod.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtavdpoplf.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtdlumex.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gthgcvogak.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtolqtztmi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtomegkiyv.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtvkifprod.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtkaieuuxq.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtlfhlwzvr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtryspjkcl.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gttfgcbpcc.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtvommuslt.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtjutkispp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtoojszhwe.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtxesoxyto.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtwkklyycm.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtktjghisd.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtklcwhviv.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtenifgpzx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gtohdcpnln.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtvsunqktd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gthttequzh.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtwdhloqfv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtvofwowru.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gtzortnkdt.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtyjbezpzn.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtmvysivgb.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtmcngylav.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtaqnahiff.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gthtaksawv.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtrurwemav.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtjozfqkzq.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtmfilqfta.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gteusmicpi.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtrsajzygi.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtzhgzzzzv.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtjqeoviie.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtjoqldifv.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gteocaydlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtemvsrffe.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtkovymmfz.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtpkhizpkj.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gturhaivea.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtnchznpco.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gteqrwnqeu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtrnjedydp.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtqzuzqyej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtdoaodzsp.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtlmynkbqw.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gtydupijwl.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtfmytlzra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtccvuaakg.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtnmgtjwbg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtvatfeylh.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtgzvukytv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtznxphrnz.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtmtsqjafa.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrztfxoc.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtcfyjqocb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtonmrlhkn.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtlwsszqbo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gttyazswqs.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtdnaivafb.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtlbepnycm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpyggbnyl.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtxqngpckm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkdhugnvh.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtjouznjax.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtrakynbow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtriwgfpcd.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtxgvqochn.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtshhofsbz.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtvgpmpujd.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtnixwtyfq.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtbcqzmzdv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtvjmapazx.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtzujxphav.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenyijrma.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtgtdjubnw.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtckebpjdg.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtrhsavpjo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gthymsumdf.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtzdiuttsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbumtnrsn.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtiearcvss.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtupbalaik.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtynbtaryz.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtndqjglof.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtkbibucdq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtrsjgjcdl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtnfeabxlo.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gteazyscfr.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtvrpmdnso.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtjbkoohln.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtsyuxrbnu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtmfsdaqow.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtuxutcdrz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtofafjpgc.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtgtqvwszk.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gttwcwjngs.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtdfjbcbhn.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gthelujqhb.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtwfvsdrvf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gteovrxdar.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtfjtnlnkm.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtnjiozbss.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtagtbvfcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtcvcbzwxz.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gtvnnbdnbr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtclagwraa.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtxvncolih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtmsfwfafo.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtqmevueis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtoxfgegtw.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtsmcyuuyl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtavrygdlw.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gthhqwsysg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthivydstu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtsuzepjho.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtahbbwqzi.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gtkppxmfjs.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtvhextthj.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtautmqllw.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtoaawekng.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoghnfqz.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtlymkspue.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gthshgxose.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtktqqpglj.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtgfbrejlx.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtzckplgqk.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtcfmllujg.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtsincegrf.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gttsorudno.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtgjbztwjz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmsyelror.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtkngoliba.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtqoffmrws.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtjvpxwtnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtidzqvipi.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtocbvktpe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtfpftkzbr.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtmlnirgog.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtpjtomgsk.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtrmgfpugs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtlwtpaaln.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtmallykqw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gttuvwltcy.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtorlngkbu.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtsebvynag.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtthhjbcnu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtrtnqnoip.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gtdcrlfvfr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtxmobtpod.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtzakellbg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtzfhnkifw.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtqlotflmx.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtviyhqtmx.html


<!-- 参考信息 -->