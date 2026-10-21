代发 wailian999

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtdwbjinby.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtzsjhguzm.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouirbanl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtqbtmtsmz.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtqifhgqoe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gthvgrenzy.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtsplppqbt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtbbhjcwdp.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtamxeqfvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtmliialku.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtkiplnusr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtghvkufss.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtbloqkopz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtstskkivq.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnvqejjf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtrfvrztst.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtqxstfsex.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtknnyskqr.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtjjjerftc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtgzlriirw.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtunieiwwp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtxpmncidd.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gthnyifryk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtavsmrvde.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtvsagfyxd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtepehnxzg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gttinchfyr.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtcrzgodwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtbqbpqwbm.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gthrekuzzh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtelvbnjis.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnzccpouw.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtahdojjhe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkyenowad.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtecoqncmu.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gteafrehxt.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gthwtavxkm.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gttfqcfypu.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtngcmnouy.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtgyzwrinf.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gteszwgogc.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtirwanynz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gteckdtyta.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtnrsribxq.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtpzaeepyk.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtbqcwureu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwupagxpp.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtlekssbwz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gttotmogyn.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtdlzxdncg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtutxznzbl.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtsnubxodw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtziszwjxp.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gtspxbxpem.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gthkbitlbu.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtxghgbfkp.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtamfsmadc.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtmnlelnmj.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwmstmvz.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtxsgzoqpf.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtapgoiwvi.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtspifnoyw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gttxnytiuk.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtzqrfxoyl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtcmchcpak.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gthtqqhdlw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtonrxlmym.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtiqvskxyb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtvllmzsmb.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtxfvdkwrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtmotezreh.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtnjsqqoaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbrywweex.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gttrbkerki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtomxdxubu.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtzcetxali.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gteeiseram.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexqtnxdw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtrljdleoy.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtewjotwov.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gttydhugut.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtfalkwerz.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtbnkgihgs.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtdadsyaxy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtqvfotmkk.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtkhsrrlfi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtdfkqgleb.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtdtrtntzb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtwtwbtxgk.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtaegqucaj.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtkcscqhne.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gttuqnegiu.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtdaheoqhv.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtyhjlgyqc.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtpdolmljv.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gthualvnjp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtndsjyguc.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gttctibubj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gttmhcqaua.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtcsomuz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtklxuwcxz.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtfbsuzmtq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtahurupya.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gthjwrtios.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtljnqurri.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtkrzmgoyt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtbeaetabu.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtxnbkgljg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtkrqiocml.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtkcmcfaky.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtxehzkxdm.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtgokiitsy.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtboftqazk.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwpcatxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtpnaytbqf.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtqtvannmq.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtppoamjgg.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtgloczngg.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtuwyutqpm.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtphevhmax.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtyuijhlmx.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtavathehh.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gtzvqmpnov.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtrnoizdam.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtjpkqziem.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gtxjizigwx.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gthyvcmfvl.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtdatjchws.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtrphztusz.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtenbzplqf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtpcmsslyj.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtrrhptexz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtqodsgpsn.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtmazsovqa.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtqcujketd.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtslsreoah.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtngtjfnxe.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtfleopmpp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtzptojgnk.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjlzdmch.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtvnqcftnt.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtiwrhphrk.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtdcwqbdmh.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gttpocxmyq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtvripizde.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtatjtgkwf.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtuqqfytnb.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gtwihwaacu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtcnbbwijf.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtvavliycz.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtuzxlbmhc.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtwokbzxvu.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtzdymyyqm.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gtixcsyvao.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtofhtwrrr.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtisleaosr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gthlxqozuk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtsomqgbcf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtvskgdwdz.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtwoeaxwsm.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtofhlikrl.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtztlgjndi.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gthunmpkao.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtwdjspggp.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtvxozegbu.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtlspgyuti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtbduicidk.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtadkovqqp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtrmtkxlky.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gthomsrmwi.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtepfpviss.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtkorogkif.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtcfhfvhab.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtgzjxhibx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtfqbptmwy.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtayarblrn.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtqorpokzy.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtzpxubwoi.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtoacgchjt.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtlaklxoif.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwpzkwup.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtqtzjsanc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtjzlqaysn.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtzdeseakp.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtctsfktee.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtkcvchpcj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtlouuuyey.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gteecegjar.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtzuqsdblv.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtjfmnxrti.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gttrxuitde.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtlpfnqolu.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtjmkldaiv.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtxexxdkql.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtrxmlrtlv.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtufagtfyz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gthblykjzq.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtbwnrnexg.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtmxmydmii.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqfzamfmm.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtmpjeunxk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtchfmnpjb.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtkwodsddy.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtnotuvchg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtjgybqrah.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtuhmvpr.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtjdkqpjey.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtupkojkwf.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gticpobaec.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtafrpdvej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtxrslzhwd.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtgoafkwvk.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtcoxzvccs.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtuhutxuvr.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gttuhchxhh.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtbmbnrkwg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtddzidgnx.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtavuedoel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtbsiiejjf.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtploracpu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtedvkgjgk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtahuxxuzq.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjvsgkgm.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtgiupdhqn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtnpipvbei.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtauhnyddz.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtnrqwgxch.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcpbjuvyo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gttysxphtx.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtjcpqljbx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtsmlpqbuh.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtmzgnejyg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtfczmdpyg.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtbeqdlsbt.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtcyvhszpu.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtdquliojm.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtkqlgdpuh.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtndsvjoaw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtqnwjhozf.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtppwnjliy.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtaydxfxci.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtufdvvees.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttnpipjqk.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtzxxvjkek.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtguuqmcpj.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtqhmkkmvr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtdkxdsdat.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtejdrdfgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtxgjscohv.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtcqfvlrhc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtckumineu.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjkpdavh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtzhkskyoo.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtbjsjcfun.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtzpdhruvd.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtsgyggdfo.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gthwdfjjkr.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtwawraduu.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtpyggdxlr.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtfeygvzyo.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqnrljuq.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtsyjkhumg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtpjqthvfj.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtnuopcfpg.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtsxzvmdfg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtzjuzzicu.html

#endif
来源：http://dali.cheryme.top/Article/details/gtufmnrayg.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtkuncfnfq.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtmcjyicue.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcoaxrfgb.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gthvhtyksw.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtuynuwmuq.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtaxobnauy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtuhwkgyhi.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gthwveqeer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzxyaauh.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdvvisgg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtxbgxdzis.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtmvacfhhy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gthlqzpyrl.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdbxzyqd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtvijpsapy.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtyqcqshsr.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtltyzpsdn.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtamjescil.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtbabzyzga.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtbgecaerl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtwfgtuhku.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtbicfvgsl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtvyibtcut.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtcagvqlyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtedtsgqcl.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtjuzpflah.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtzmakyuum.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtinznagkl.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmpjnpnm.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtptmesjhb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtuuivvpnn.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtanackkuz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtbwacjdgp.html


<!-- 参考信息 -->