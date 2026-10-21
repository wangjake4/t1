代发 wailian999

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gtziemptek.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjvgicbml.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtalopndkg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtzojxwhhh.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtehudxjfe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtpnmcznej.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gthuuqkwkh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiqdnydl.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtmfotuqky.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtokjzfslt.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtwkwmxvbb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtvuhbimms.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtjqdythuh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtlkhdppkv.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtwvivdxxx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtfbtiqqod.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtxufsyyxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtbrlxuftq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtepafviup.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtakgogpkk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtwfdxsxyo.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtskomydia.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtbbxxxisp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtahfepksl.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtvrsbollk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxcctxvcw.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtstqffvfw.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtgxwzukrx.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtnivpledm.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtljwcovug.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtrrwlehuy.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtepyfigxz.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtrefsnmmd.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtwyswuhea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtucnkwgyd.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtodsemnjg.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtsyvkjjqh.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gthvfwangd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtkrgpkzln.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtntryfnwb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtjrjlzjcs.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtkptmpwqg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtkmpcotll.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtianyucxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtsnotpsrp.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtrmjxxkcy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gthbtqumpk.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtsrjqvrfz.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtvahmnwkp.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapeftime.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gthrdflore.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtzboiryle.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtwmwamiqp.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdwtuldcg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtojbfsnhm.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtdhbmmnuq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gthhyxmgwf.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtoqfggfrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtkehsivgq.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtecruyagt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtibqrbhkw.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtlkrvrqiw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtevaugmvv.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtotuccdsw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtjupouvka.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtemixkfsd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gthncufyax.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtcddhbjrf.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtownrnlid.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtkqtklolt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtxrbfrsvf.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtpirkigeo.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtbbnwzutb.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtrzsrlmvi.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtaykgihwy.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtrhivtalv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtxpfrwrpx.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtfherfvih.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtxtrmnzlj.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtckvjlscz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtergmjali.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtbghddoqo.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gteuthuabq.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtvtuejbhl.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjavefpry.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtycjciycp.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtjeyjpase.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtpybraqkb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtqsratngi.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtdfqavnii.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtkvuarxlg.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtfrlmnvzp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorbabfme.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtdktrjfcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglerjtsv.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtshtjswsd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtgydujmae.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtidtctnkk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtnwegeymm.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtldjtarjg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtvuxtbmfp.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtiethskpg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtgcvvgpbf.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtspmftodz.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtsrtfrhfd.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtvctcntqy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtdlokxkeh.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtmsdldevm.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtlywlfzya.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtekrafabe.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtngyecoxf.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gttbybvgxo.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtpyihfckq.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtcbyqekmx.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtlxncqkht.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaqxpwfa.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtiwtxqbmy.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtruntymks.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtbwzcrbts.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtrugidyyc.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gthgffuwzc.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtrmmyccty.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtbxznmdnh.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtneiftuqu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtxphknnhm.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtewgndfso.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtgjqpkknk.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtjxmynjxh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtlmmxvspt.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtpfzphmbg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtgmglmuwh.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtdqeokxry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gttsyxctgk.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtphkbtees.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayuihhho.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtonagztws.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtdzbivqtt.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gttihzyutv.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtzarmcczp.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtumlwogpt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtmovsakbk.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtccmawshi.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gttfydpphg.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtezvrgfcq.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtxlsvadco.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtetaqdrbw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtumfoxnlb.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtmfqsdnoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftguwbjc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtirodkwrc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtuftamvtd.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtnbanloap.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtbfzblzum.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtqcymfjsl.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaknxmgp.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtuzvafxyq.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtgvuawnhi.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtnrdhgzoq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtpnukvqlf.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gttfkhloss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtjrmrxzdn.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtaftzyyja.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtepyceins.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtvfcnhekb.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtlxlmcojm.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtkkwmxlvi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtsnmzmvyd.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtzyzibnwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtevwcfowp.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtbbewfymw.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtotjbeytx.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtmjuzygym.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtocfifsfb.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtgvepuuoj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtyjpfxlkc.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtpofzklxt.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtimohmmru.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtyclpjfge.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtcopuhlkr.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtkozgtzcw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtffawqiwo.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtkegcuxqn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtjeszvynk.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtfrfrhvxa.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtgieimgbc.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtdprxgzmx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtkqjhuyof.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtnevwdmhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gthvvmkuls.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtjrjaigib.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtxxatdmtz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaygjwdat.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtyrctqlne.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyjohgkiv.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtzeygnkfr.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtsvfswbhf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtpbrjqmms.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gthbbxikdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtllglcrot.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqamhgkvu.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtwonnwuzb.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtrsqxjdif.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gteopdalla.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtduvjqfzy.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtnbmujgiq.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtcbdteiwb.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gthtptcevf.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtlvmwxjwn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtjzvfijmk.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtdobrymll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtiuyrsefn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtumdmapxa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtogexwszn.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtqxzsjkak.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gttiwvbqcq.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtuftluijw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtjtvcdcdv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtfpwqkune.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtqjirgqwj.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtffiwxhcp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtdpdwvjoc.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gttuoswbsz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtmplsbwne.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtseephstw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtqkadrffr.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gttevqduat.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gtcvcjqwqw.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtkxhspees.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtqrsvombl.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtaaxclhej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtneczaxgs.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtjwtnlcfz.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gtlzzyrkrh.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gttmfphwcu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtllxiuelq.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxigfwrtw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtaqjbmqmt.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtfsgsuizp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtpdjusjho.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkwmwyjg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtzasihxwg.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtebzhqulb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtjwjzpnnl.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtctqenfjc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtwakkqtau.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtjspaauvz.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtlfpjukax.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtucgbvuui.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtzatltlap.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtpqtmxncz.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtcymqdvmi.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtorclulaw.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtqudigune.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtjoauxrft.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtbtdoimbe.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtjzinvfmx.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtspwdepcg.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnpzqhxg.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gttagmfydt.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtytsrctlf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtudolwygy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gthdpijpep.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmjzkwnqv.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtwaybbyvk.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtrekimazg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gthgxrtkbq.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtgjadzyfm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjzuqlkho.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtpdrhvowx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtuuaakbts.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtiqsgzsfp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtnldntcvw.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtmgtmvmlu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtwixdurvn.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gtvvnncawc.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtuogbjyzv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtkagjnoud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtcmwphfck.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtcvlycydr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnaxttjn.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtzkjvooxt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtmuqgiztq.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtewlgqyaf.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtzqxjgzzi.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtavmipknh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtfnmwwylt.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtmhwaoifx.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtqgxetesb.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtxxltvmmu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtrpioorbe.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gtjqhrbylo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtcsiosvdk.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtvmyznnzh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzqkqzny.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtcydwppsb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtnhvsqwpa.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gttrhsdkgl.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gttqikgydp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtiyfgoblt.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtmhslhrdc.html


<!-- 参考信息 -->