代发 wailian999

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtdmblwtzn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtedjkdkgg.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtavdzwjfv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtsgvkdtqk.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadgzwocm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtmmzoccib.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkgcdwcf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtsezmrzrq.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtkwhlqlgm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtajexxgko.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtaaxzklch.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmsdstzps.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtlqokkclf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtolfjwijj.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtvpvmcssd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtzfbkobmd.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtjjerivjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtueyueyhj.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gtnigqouyc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gttencqygl.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtqxfbxfog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtfdcxerrt.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtvtnjssur.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gtsdyzgzwx.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtqvtcsbto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtdwcsousq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzxmpaxa.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtlkymdqmd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtsroeyxzl.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtzdqoobkj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gttveiiypv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmytvyldn.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtetvjgbfv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtilssxxuq.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtjcwclmtr.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtqkmvvqgd.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtdlxtoilj.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtohrmiwnc.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtcwgrzjxp.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtggqirniv.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnpiwydd.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtleadgsrh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtwecwryur.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtpiglupjy.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtybwcomyg.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtcqmddybt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtyabstdoi.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtiurtbehq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtbozvuxim.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtsbpiqcgq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gtusqscirp.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtwbdougoe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gticvccsgo.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtbifauymk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsvgvzby.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtjpzevemg.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtbrzasrhj.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtahnuwldu.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtojbqbure.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtmowvkoih.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtgmulqjom.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrnvofojk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtddcxhvrs.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtlbtnbowr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtzonembwg.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gttzcaibba.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbcoekre.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtqezhxsbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtzpindzoe.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtkxpbbgfy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtirrelrko.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtgbltrmbe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtvbjieclo.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarvrbjlo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gthfqiqyjy.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtyjhjrefx.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtzrbujzzp.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtpaaokoqd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtkonfecey.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtnssbgfwf.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtnhssdgjh.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtjytwtexg.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtmedmdllt.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtxzdaumoy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsbampck.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtsvwzxucb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtxalulydf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtzuxjwskd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtxukxpfou.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gtmnuqujia.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtrtcrieyj.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtucwpmocp.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtgtkmwwzn.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtitrszprn.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtyppobars.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtvtfjmazr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllapufgv.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtzrbwfjcb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtwodpdbqc.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtjvjqjmqj.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtasbwzufh.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtifkdrvci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtqogbvwhm.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtyifbejfd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtoatsmzcc.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtzcgmdmiw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtfnmsujey.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtghjupjxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtarmdzzhv.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtajnmkhkv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtrgpsaoco.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtrsgjmmmy.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtedvyesdo.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gthmrcizbo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtordjzfip.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtxlcmywsk.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvuhmfsd.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtcpoojpyp.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtqaecubzq.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtxawbriql.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtohutbapa.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtadwwaeig.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtzlqdvfyz.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gtgenpbyvi.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtqpjkqcbk.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtxvrrcmrv.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtkyqnqzad.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gteegovfun.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtfzqzmxpd.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtmozppkwp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtipbrvemt.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtjqmidbdf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtbnjyimzi.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtwppesabr.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplkegdcb.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcmwyvgw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtbbkxypwe.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtgxsmbnvn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtmtrtcnjg.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtwqyygkdl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtlkhabkkk.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtmjrnidvn.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtpqxmluyq.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtzoasjchh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtumdeftxi.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtpybaufbq.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtgfnelneq.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtgsnmnhte.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gthnjkohdp.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntvvgxao.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtavuytdlw.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtbougslxm.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gtauvnkdhb.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtllatgfol.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtczrbzpsm.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gthibyzgmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtbuzbzhby.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtzfzihikx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtfpxlnxtj.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtaipkvfhn.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtoxdnsyas.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtjfybymqb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gttsnknmfu.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtqqdhfcuf.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtccmlldqj.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzflwttyt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtfjedrakj.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gttcxjupes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtaphonxun.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtljxbafco.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtomrskcpw.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtffzjdwhz.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtvjxbgegd.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtgwdireef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtzkbcokdo.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtpdimyezv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtfflapllm.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtwruvsxpj.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtschkvhgj.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtkuixehvf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtnvfqdslu.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtcamemzuw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtkueduqsg.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtbcdxdqce.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtrgbvzsbp.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtfmpzutum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtegblkubi.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpejnomdo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtnncjgaiw.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtgllrzmew.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtiihtmoqn.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gttckicagu.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtewzwylkp.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtuimbrpxi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gthyiezcpt.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gthdxsdquw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gtrsrdeock.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtidarvevr.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtrpokybau.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyazdtihl.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtyeyyonvy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpnyidmtj.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtrfynlkoe.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbpstbkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtduemdxtv.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gttpomftre.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtzkxeback.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtotuaelre.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtwnqbanrd.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtfdckzncm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gthaglpqff.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtwwmaefba.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtizvnslgt.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtkbvtgzee.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtfhxvzmfj.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtsomkahji.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtjfxmyxsh.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkkrijrc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtogfnofnn.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gttfhedlrx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtmzkqelmk.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtuptbsdhe.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtwtsmyzrn.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtiqbunbzj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtztmqgsem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtuphztexn.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtetutnrwc.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtbvlwwigj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtjjbgkxaf.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gttdnjhats.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gturxuvvzu.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtkmargojt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtmfczfcpc.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtxdtyswkx.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtqzzrydir.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtgfvnqvla.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtuqxfyxvq.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtrkercrut.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtzzdgfrkd.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtwiaggxiy.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtbgbeewrz.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtfvcutawq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtgmiaysrb.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtoisspkmz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtybzexylr.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtmbgitula.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtmrufevim.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtjzifmqyw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtwrinoium.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtwmtfkxwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtdricerag.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gttdjfgcng.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gthhzfcacm.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtvbnhcokl.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtocxdiout.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gthulfiwhu.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gtndkunrcn.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtbgtskhek.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gttwfezzhu.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtpzsfwnwf.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtyeoorftj.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyrthrdcf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtrrpczkjn.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadqsyiwz.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtpbuxmsht.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtllqipwoi.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtbgvzieud.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtnpkuxevc.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gthcxnjguh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtsfibonlr.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtrtoxpxec.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtfbdbhgei.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtjdhyamvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtsaplhqnx.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtfbnabfzh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtriegyhap.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtfokybyog.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtkkonlpiu.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtzegukcun.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtfcltyrzv.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtaicsugte.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtfkwhkmfn.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtgbiertib.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtjjinlxgd.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtwqkqppot.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtocyvfqbl.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtqsjnjbew.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtziyycayx.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtbwmeauoc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtxvmrfjmv.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtyyhcbvav.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtbkuscehn.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtmzqmyuhz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtsieyhshw.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtylnsrfzm.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gttxputjws.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtooscjrfc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtrhidtxgc.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtetyzpscc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtshtrqkxa.html


<!-- 参考信息 -->