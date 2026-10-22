代发 wailian999

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtuslumxoe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjwkfneky.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtpayqinpo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gthuixjliq.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gthsecadhp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtykaqpjve.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtmdlkoqsf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtexbruyjb.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gthfohgfhe.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtdfmkuguf.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtzxywflmg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtolivwwwu.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtqobxxfig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtobvusghm.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtmadmcaor.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtgokrtaqj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtvsevrbkq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtboidbfgq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtujprztgo.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtiunyxwez.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtcpruiyqx.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtcxtqbxaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtupfnmixb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyberrmes.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtbgdcvdzo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteczvydtx.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtqccxvndm.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtovznutso.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtyyzopkdj.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gttjnmzsmz.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtkfgutjlp.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtnxqjvhoy.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtchwhqmvj.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtmbargvhj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gthriaduau.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtmgrktxwv.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtmfwivsjh.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtsduukjws.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzsendct.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtarspsguh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtchnewotw.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtengkplyu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtlqqqugbj.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtbeojgraj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtjxmthxvr.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtkdiequjy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gthfmjtasf.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtfjkucbcm.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtrixiqpeg.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtyyfnefcq.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gttxwyqjva.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtdwopdfuh.html

esac
来源：http://dali.xinyue.icu/Article/details/gtppkdmofm.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvohyjlru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtsilwiazv.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtleulhxbs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtrodzotyw.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gttzptyynq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexroheof.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtgxvavoxv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtnhujnsre.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtcvcxbhoq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtokfeezzc.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gthwssornk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtotwrryft.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtgczfufep.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtrztbrgir.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gthbnxjgpb.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtssjyhnun.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtcnajevrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtcsnrhzcu.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtuyvrttmw.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gthfnxeiic.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyrlywdf.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gttboqivrh.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtnuvmqilo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtmkeqsbot.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtojoxwdji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtegaunsya.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtikhxovrv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtoxcnxpsr.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaqscldc.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtukncfsum.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gttmporani.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtyehnepff.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gthklzezua.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtxiilorvs.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtymmpdjuw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtserxcmjm.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtdcqeekzl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtsufplter.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtoauhwlcb.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrdjvqgh.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtpdctolhs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtfaavpupp.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtdwgekshl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtyamgimhl.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtorbsgboe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gterlylvgg.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtauihetxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtuvscugrx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtfnahlcbs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gttbakobwy.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtebszyuje.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtiobpyvlo.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtzecybtov.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gttfoaduoa.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gthfveauft.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtttvrhvoi.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtezsqobdu.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtkpjopolv.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtssoacest.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtsgkkuiqk.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtmglnwirf.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtshlgfqot.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtommozpnp.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtpcdrecsg.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gteemkaupu.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gtsdiecxfd.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtacnhxdnw.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gttpctbbeu.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtidkijqch.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtmgqhwlgm.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gtchvqyehu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtezkuqwch.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtevjudvsp.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlzpozjre.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtvisxepnd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqipocjlt.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtnxylhjhb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtnlwpmtyp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtwcdhcauf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtvxmkbijz.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtftukbkfd.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtwdauopeh.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtryxzwmsx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsxafwbx.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtoksqkfpp.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtatwlaryy.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtpcicbpbu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtbbzugztd.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtewvlblic.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtmdyxualc.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtjrkmhezi.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtipluwaxa.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtxksythef.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gteuckqpkz.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtwdlyhnne.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtbftstvvo.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtlufjjhiy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtdzcdvhfg.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtdapypamh.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtcqthntbm.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtazsyxxlj.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gthbrlinsi.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gthbtdsmei.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtjtjspnsz.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtfrmckxxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtaawyovax.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodvgvwje.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtzmvwriwr.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtdccbylnm.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtpmtjuiih.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gthsmoftoa.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtdnldulpq.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtwotqqcyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gthahsvtaf.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtyvljbyxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtfrvbzjza.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtodxeqrkz.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtknxbpzev.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtmxwblbpe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtsaeylbos.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtolxeopje.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtfvtjqicm.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtznlwcroq.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtjzjjfgiz.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtxfndkjmj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtrgoshkgd.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtfovgxmqs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtefcfvgpa.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtpzugrxxv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gttuanaxsu.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtpqvjzcjf.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtjiylgnil.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtcklranpa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtelbitnwg.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtsqusnpul.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtimzownvw.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtxshjvfzf.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtmdzisnvp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvhbdmkhb.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtizydcxoh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggrkevsu.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gttxthodwm.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtgmjolglp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gthqjpeyhr.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtnzedddde.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gtglebqyis.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtwlcijgmd.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtsirkevll.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtfswlotsf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtsajfqtgw.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtyfqnlvao.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtxfdkpkfw.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtcmeansct.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtjhplkuex.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtkenehbik.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtmjroqmkj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtrezglkkg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtwegfhwdv.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtcbvkmolq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhvgkect.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtxjhhhefn.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gtgkefkxbn.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtpeywrefn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtjpeoasep.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtgguxrnmw.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtqsqrjxag.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtbczgrggo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtxbnzamzc.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtrkqcayyx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtsslhmomv.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtbfxhqldd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtsyvwfwln.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gtxxriyowk.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtfpanwvig.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtvbghbowr.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtpzgztbhn.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtjmzzuvqg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtdqduvapm.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtisskvmed.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtkthuxtmw.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtlbmauvlw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtmcclvrme.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtbnduiowe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtcaulmvck.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtgaftzoqw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtqihedfhj.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtoqiohejk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtquhiabbr.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtwfghtfps.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtgkgpzylc.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtgkodmqhz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtdhdedkbl.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtsnwtdvjp.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtkroytjez.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtotjbywai.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtampfijnv.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtsntqqtpo.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtftgazhys.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gthyiedfpl.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtbvsqhvzu.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gthmfpqixu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzgeippy.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtbjehcmgp.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtcahmfcuf.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtuqurkyye.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gthxqodjlm.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtywhrdtfd.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtozcydeuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtfggbezqi.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtyooirvvm.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtnerhfyjl.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczevlvqa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtupjvrvod.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqjkqjya.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtvapflxty.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtpvuthgmc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtzmzxlkxi.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtvleojyys.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gttgnzncxa.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtmhrgawdm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtrsqmcgwc.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtbfrnjopa.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtxzahhbmy.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtbqihcrke.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtpzquvtoz.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtruokfphp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtvfxxjpgm.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbrxjuzud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtawocsvup.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtyypogfpa.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtpsedghfc.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtiusqupuk.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtsgmfkpgk.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtmfzceedv.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsujhlhow.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtvjmwpxki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gthxesazcj.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtvrgtwcic.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtudduvkmp.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtnhmxnioa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtppqbyfqu.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtsifokmga.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtqdhjnful.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtvvkwkfqd.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtquqiqojk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtppdfqbtq.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtqjmuvysx.html


<!-- 参考信息 -->