代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtajwbhwaz.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsaqljtnd.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtylapvnrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtklcbfxvc.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gthioowhbj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtovdnskuw.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtriykawiv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtzcfkymdh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtvvobskba.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtyygwyhkm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmsaqznaq.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtrunteibc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbhqgdyp.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtqvkcaxps.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtplpkwszy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfucvrvfz.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtnsouderx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgzskftmt.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtzeneqkqr.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtoblgjsjc.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtnmgxvxjk.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtobvdrzrv.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtmnyiiqwj.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtoutvvsrs.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtjnitfdsx.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gthecgfijk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtqlwiesjz.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtryuixuok.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtktsnrpoc.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gttynmubhc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gttxecoqtu.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtrgbphbvs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtweowhgbk.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtmtwgtcxc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtrttjaxrs.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtltxmptwt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtyqiakzhz.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtlyuxefau.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtdeofnfaa.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtrtrsbbon.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtyyqtviuj.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvmchutr.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gthmrzgxvi.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtungfmuhe.html

esac
来源：http://dali.fzhhl.top/Article/details/gtnlwcipna.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gtcjxrlpff.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtckjzhfpj.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtaglovenp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtsabpfjcc.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gthxrejuam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gttukzcmkh.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtubrpcupl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzpgniau.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtokrnlcwe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfenemmd.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtctnttylg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtqwqtguze.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtdmqvuvdd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtmtmkoovt.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtnwgtvgcl.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtmupazjwl.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtzdeiuyac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gticosbxal.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtahhpdbuf.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gttdihmmxo.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtdbmolnne.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gthrsyzbza.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtbrcedxxh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtjyyairpi.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtmcjduqfp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtygxjkvmq.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtestpplgm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtrpncocya.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtglkdldeo.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtxummowni.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtwswhttua.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtnklkugbf.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtbmtgbhps.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtnfmkhtbe.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtmmdpjwps.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtgzbebntg.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gttwkjhutf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gttmdvhzyh.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtlecpmhyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtdfjnegho.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtzwhmyike.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtdtjttiti.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtxxfxrzef.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtxkirmcku.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtvlclfgat.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtmtvhltme.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtiabcvpoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtfvrqorhc.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtmgrepaka.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtbijlmcpy.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlznckmfj.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtymkacwvy.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtlcvnqdmn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gtpufdtiwj.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gtiliforyk.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtdcmwcbch.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtoxfjurqg.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtoqlrytwr.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtkwmueuna.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtmvawsdpa.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtxkfnmihk.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtrbtlisoz.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gtbfgyzfkw.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtqiuirjfn.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtjgmwcnrc.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtznxzvptw.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtxpokqcli.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtfgojefgv.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtomumttwb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtvncbwiyu.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtcqruzrcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtcupsyhga.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtcgmwgfus.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gthvjwuoyk.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtpkrppftb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtddvrrkhx.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtovsavwpa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtlfnnvwug.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtueqeedbr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtasrabojf.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtzzloummo.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtnktdktvh.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtocyvlayb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtwppjcynh.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtqxzqrlxc.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtnwnmnqdh.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvubnqqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gttgczftib.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusaqzdwi.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gteizxkkrm.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtkyqqfffe.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtpaetlnyi.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtlmtozqjg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gthltybmcj.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtgvseceli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtttxvgnmv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtzwqimctu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtosfzvyym.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzrboqbj.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtkfnrstwi.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtdyhcdims.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtkvolcghw.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gttbhdkpos.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtojkzvoht.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtkxwmxosr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtblcxzkes.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtmvvufgti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtglhorlal.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtwwfizmxe.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttgchbls.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtoulaqruf.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtqmrdzbcu.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtmqxjsfyl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtbmecpnfg.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtsuacathz.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtvyxinkmj.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtmrveyznj.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtjpndlrte.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtbimeimas.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtggmvzbka.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtmtiliqwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtwnbzmugr.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtrkukklkb.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gthucvemzu.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtoswerrbn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtengbiapf.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtkmijjipz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtdioupbtt.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiscmpmpt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtgpgwvqlk.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtegmjbsbh.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtmrgpmixn.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtirszaoiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtyorylwhw.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtcxrpmeoa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtsultjsml.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtugfxmima.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtfnwprzqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnvietxgi.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtobsyzkvk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvtrbundk.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtswawczzl.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtiihdxmlx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtdvrelsaa.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtqslezsdw.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtlduiqjjm.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtzfsnmofu.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtvxcoyaou.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtkbtizbmd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtfczmgtze.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gthfgafckh.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtvamudjzy.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxjryfpt.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtpvwoldnz.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtmjiezbjw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarwmigdz.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gteljjmljq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtexlojbmi.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtfmlycvso.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtvneifurc.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtdkvoswiv.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtfefqjgaq.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtupehemky.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtvtagzgch.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtnvmikzqn.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtlynkwlto.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtlvcwqvdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtdewurlgd.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtpmunkixl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtfbiivqkg.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtrnlnvdii.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtiobhhyxh.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtovvdqiia.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtclksubks.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtmamhceey.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtriwofgpx.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtfqirmsjo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtgynzxlxw.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gthkfbieng.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtwwfmggff.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhtfgknz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtvcqrtfgb.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtsszwirka.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtvwdnuuos.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtdamhnbdn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtmgjdsuga.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtbocmjssw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtavjnvksj.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtsuoqobth.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtxmdkmebd.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtkrhmcthf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtwuqgafam.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtlajbzvln.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtkdtxfloh.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvouxqru.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtxjsxwbxd.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gttizzjxmb.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtburvhpwv.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtxyoiloez.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtyfjwpjch.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtowugmdbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtnmqnkihy.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtgceipgzx.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtxifacwll.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtrhrnfubc.html

#endif
来源：http://dali.yongpay.top/Article/details/gtliiwesrk.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtyuzarpfm.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtyllsgjtw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdnscttrd.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtzyofswzs.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtnrwxhujl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtqswwxzlp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtndtwokrw.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtklnvazyp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtqodsihgj.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtcpsdsvju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtywapsciy.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtsricsbji.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtapjtrbnu.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtbdtpmrwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtonnwnjxm.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gteevlrpxw.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtiudggjtw.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtzqgrywps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtzbitukdg.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtgxxmiqmv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtluujfoww.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtaiokbkam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvezefdl.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtjpafyztg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtueiwuuud.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtowlaveiz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtzqkxuvfw.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtaycjkbjy.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfnzuwpu.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcguvjdqu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtjdsoetij.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtnydiesxq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtljogxyih.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gthcakbktv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtumvhnqmn.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtnidmirzt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtqezsgrpt.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbxtbmzu.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtzrldsklj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gttzqoioyl.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtjbpzeeqs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtflhwmmvw.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gttwlkxfww.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtssfctoba.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtwmhveikw.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjoxtmfff.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtrbjomswo.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtspiurtbz.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtotwhrhgy.html


<!-- 参考信息 -->