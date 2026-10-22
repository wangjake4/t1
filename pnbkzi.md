代发 wailian999

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtnjqxsnlk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtuhjujnpj.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtqzojwdqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtjyodxwhz.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtxvhvvkvr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcigopfbx.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtuuxuktyh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxujbsbxj.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtuouugiou.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtekbvywzw.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtijuilrig.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtrtdbfaes.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtyyfbuabm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gttyrgzdks.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtdkhoissx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtknqztmyz.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtcogwctfp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gtypkumggs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtyrxuucid.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtffcaaxdi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtnuinducn.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtrlxtwdci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtpuiladvn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbqznlgss.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gthgxzmdjs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqnlvvzy.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzydyqqu.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gteacgnttt.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtveacaldr.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtrpadyvpu.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtdplfrlln.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtchcjebsp.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtrjoibfgi.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtibcdbeun.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtejjrpwxz.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gticilinih.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcdltydv.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtqhgsckxu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtcgfttmar.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtlhgpgdlj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtmtrjrzjp.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gttdyktugz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtarxzhbsq.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtijymejxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtzkusuhbc.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtjfoldsgg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejkiylxl.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtdarsgmau.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtvptwjauj.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gttazsnmxy.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtwppmqepr.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtapkqhdno.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtermvxdyf.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtddszfzlf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gthwtzafnc.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtijewpxlt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtodyjvotd.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtguubqjrs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtjalqamfb.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtdzhmlsvs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtdxckkxsg.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtsedspolx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtcbbyrlqw.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtxzxmkmob.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtjyanpapk.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtnvmufykp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtaalpzdhb.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqgdtsuh.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gttulvjrmj.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtcgkcnwdj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtgkvbmrkt.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtogoyqkhp.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtsrxijgxh.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtmlgsefvy.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtjkoxzcnc.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtaedjhaww.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtswlbvbav.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtdkvrysql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtmhpcpuoy.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtdieujpdc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtzeuxaisb.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtovktqoxw.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtmrcjaajz.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtdhwwsgir.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmguoqisu.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwcplpqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtmetoosxl.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtmqmcnsfz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtnwworiou.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtjiqmhmbr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gtzqewqnpy.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtarpkbvyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlacstwlk.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtmzfjwczd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtsgzsmcxy.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtsybdemmz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtmsvmxdtz.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtwvjaarth.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gthcdnwtre.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gthevuifmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtptqueikd.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtdpenytub.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtgjhyoxxz.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhnzlufs.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemttzxxe.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtkaxxovxp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiufeaiqe.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gtxwpvbgde.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtuhfmgtqf.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtxixbfmph.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtupnhvsdr.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtwpwydbam.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtxhzauyau.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtnesolpuu.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtipuhpuki.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtodgadaei.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gttjzzfhdj.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbxjlpu.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gttzmymtsg.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gthpmagxky.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtweizslpx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtloqhelhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtolvdoruv.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtlwgpgetd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtwdbqniet.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtjsejxzgc.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gttbxnqinf.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtovbykgwa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxtutgnm.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtjagltfwn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtqztaapzg.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtjwsuxexc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtcrbvqmah.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gtlepgsiuf.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gthbeunbzz.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtjvodlhnz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gtyvgrbhib.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtmzfblrkk.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtaypmjhnm.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtiunckdeh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtwpzwbhnd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtduvarldc.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtksmzubyl.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtqgbmroei.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtnlclxcnu.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtztoyxshr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtggbcptmj.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtltigokpv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtjklzicoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtiywpcysx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtvgtpzhrs.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtbhbdldpn.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtpmtprmxa.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtlbiyicwq.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtrqygfbnd.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtqoxpewrz.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gteggvjgil.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtjgyweabq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtmykmraxv.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtbcmecuea.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtzyhoaisz.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtzeklkphw.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtxxifytdi.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtlkiskbwd.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtysrrclcg.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtdrgclonl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtawdrivry.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtuvxyqhde.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gthyfqnjvv.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtpnvcgmkf.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtsencoldb.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gttfpcnjdx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtnjcdmszm.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnzcjdoo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtqnezuvor.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gteijixjlx.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtsuscmwvs.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtabjeodnn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gtrwkquhrp.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtmnmcqzbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtvjhohwvy.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtobbzbsog.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtcynduhjj.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtxndrfrqx.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtkmfiffnw.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtmppeaube.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtebdqzgiy.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtqdfscyfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtrsllvihc.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gthwjdewov.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtyqzvcbdw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjoiuspbj.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtiiaxycmw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbxrvskgi.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtylzoheyk.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtkzywhklk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtjgmiuute.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtydjhrbxf.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtrkikhcha.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtgcmyyxsv.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtvtpgdzsa.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtxsaozaeq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtayyuaeel.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtjjhbvewk.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmgskjlu.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtqbykmidf.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtxieuklkh.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtizqvsxvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtzyklrzig.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtbqazezyt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtfirgaztx.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtbwglhngc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtsfgydlcn.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gthmefheip.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtixptuyzm.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtokxnuqcs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gteogoobwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtehwwnous.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtindbbcow.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtpazeiylt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmywcnrcg.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtdtzdxhrg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtlxetedtw.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtxoyccvyt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtgsqixeuz.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtarwvquzs.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtbkupzmuz.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtgcynxhnh.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtptwyshla.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtxytspcej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtjokfrdix.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtcibofdzj.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkhwtqvr.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtatlegarw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtfgsnlwkr.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtxomyfzqi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gteaovkliw.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtfrilxefc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtuymmpfgp.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gthevfbabh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtkvatmlpl.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gttcfahefm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtzikdapjq.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtbqpfiizf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtxpaykcea.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtcojbwfbp.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtttgksuqa.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtakfclkrd.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtzyqahkqk.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtwnlbddcz.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtzpcalbgv.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gteejgbshy.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtlffghbjf.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gthccxaqdf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gthexwptmi.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gttvikjigt.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtcygmivvf.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppajysif.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtjpydwblk.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtiztiorpf.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtkpuzcixv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtrcusjqyp.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtlwziqyax.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtbguedfpg.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtaevcroqq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gtjkorrfih.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtpfqnebnw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtmkgfulhs.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtwhhhqbxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtldphhcfc.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtuivzqoco.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemvytnem.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtobgkpkpl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtkuaapftr.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtvxhhruzq.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtkitwaubc.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtztqoouya.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtcssywaaq.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtmbbkuhqb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gttncikjpz.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnqevddle.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtliunqhih.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtgmcxchoz.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtcsdtnreq.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtmtqeanmv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctqmdwnp.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtggwqzwqz.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwyrpleb.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtvsbcaycr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtdgsrciei.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtqaoghpjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtrcmqwceb.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtnesqrqes.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqxybbyx.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtbpnwxxte.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtqvkdpjly.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkagrmnck.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtpmyvktes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtryghodyv.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtrdgnidnh.html


<!-- 参考信息 -->